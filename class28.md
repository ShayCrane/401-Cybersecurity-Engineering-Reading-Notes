Reading Notes <br>
Class 28<br>
Re: <br><br><br>

*The purpose of this document is to facilitate my learning of various cybersecurity topics.  It is created for my personal use, and is a summary, including paraphrasing and direct quotes, of information found in the article(s) linked within.*<br><br>

## Ethical hacking: Log tampering 101
***https://resources.infosecinstitute.com/topic/ethical-hacking-log-tampering-101/***<br><br>
<br><br>

The process in steps:<br><br>

Disable auditing
- when logs are disabled, it leaves no trail of evidence 
- reveals logging level sys admin has in place
	- allows hacker to disable only logs that would reveal the attack, going unnoticed otherwise
Clearing logs
- deletes evidence of attack
- install an executable that clears security logs with this command: clearlogs.exe -sec
	- verify by checking security logs
	- remove the .exe file (it's evidence)
- Meterpreter
- Windows Event Viewer
- In LInux, use shred tool<br><br>

Modifying logs
- can be done using a text editor<br><br>

Erasing command history
- bash retains commands history, ex.: Shred
	- history found in the file ~/.bash_history<br><br><br><br>
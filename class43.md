Reading Notes
Class 43<br>
Re: Sniffing Attacks<br><br><br>

*The purpose of this document is to facilitate my learning of various cybersecurity topics.  It is created for my personal use, and is a summary, including paraphrasing and direct quotes, of information found in the article(s) linked within.*<br><br>

## What is a Sniffing attack and How can you defend it?
***https://www.greycampus.com/blog/information-security/what-is-a-sniffing-attack-and-how-can-you-defend-it***

<br><br>
### Sniffing Attack Defined
- Uses same technology that can test telephone lines and determine quality of the call
- Technique used by criminals to perform a man-in-the-middle attack
  - intercepts and reads network traffic from the target on its way out to the internet
- stealthy attack<br><br>

### Pen Tester Use Cases
- Get usernames and passwords
- financial/bank info
- acquire and read confidential communications; email, chat, etc.
- all the above can be further used to commit identity theft
<br><br>

### Types of Sniffing
- Active
  - the sniffer floods switch with fake requests
    - this fills the CAM table (MAC addresses) in switch 
    - when CAM table full, it forces switch to act as a hub
      - network traffic is sent to all ports by the switch as a result
      - attacker can now sniff traffic from switch
<br><br>

- Passive:
  - (less common)
  - occurs at the hub on target network
  - sniffer device placed on hub will spy on network
  - hubs are uncommon, replaced by better, more secure switches
<br><br>

### Attack Implementations/Techniques
- DNS cache poinsoning
- Evil Twin Attack
- MAC Spoofing
<br><br>


### Protocols Vulnerable to Sniffing Attack
- HTTP
- TELNET
- FTP
- POP
- SNMP
<br><br>

### Top Tools Used for Sniffing Attack
- Wireshark
- dSniff
- Debookee
<br><br>

### How to Protect Yourself Against Sniffing
- Only connect to trusted networks
- Encrypt the traffic that leaves your system
- Scan and monitor your network



<br><br>



<br><br>
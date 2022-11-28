Reading Notes <br>
Class 36<br>
Re: Cross-site scripting<br><br><br>

*The purpose of this document is to facilitate my learning of various cybersecurity topics.  It is created for my personal use, and is a summary, including paraphrasing and direct quotes, of information found in the article(s) linked within.*<br><br>

## What is cross-site scripting?
***https://portswigger.net/web-security/cross-site-scripting***

- Cross-site scripting (XSS) is: 
  - a web security vulnerability that allows an attacker to compromise interacts that users have with a vulnerable application.<br><br>

- How does it work?
  - by manipulating a vulnerable website to return JavaScript code to the user's device. 
    - this fully compromises the interaction with the application. <br><br>

- Types of XSS attacks
  - Reflected XSS: malicious script comes from current HTTP request
  - Stored XSS: comes from website's database
  - DOM-based XSS: exists in client-side code, not server side code
  <br><br><br><br>
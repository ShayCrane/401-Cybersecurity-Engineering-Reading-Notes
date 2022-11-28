Reading Notes <br>
Class 39<br>
Re: Understanding SQL Injection <br><br><br>

*The purpose of this document is to facilitate my learning of various cybersecurity topics.  It is created for my personal use, and is a summary, including paraphrasing and direct quotes, of information found in the article(s) linked within.*<br><br>

## Understanding SQL Injection, Identification and Prevention
***https://www.varonis.com/blog/sql-injection-identification-and-prevention-part-1***

What is SQL
- a full programming language
- mostly used for getting data out of a database
- query = command<br><br>

*An SQL injection can be done with nothing but a web browser and basic SQL knowledge*
- an attacker can
  - extract user data
  - discover or reset credentials
  - use the above to move deeper into the system 
  - "execute arbitrary commands on our server"<br><br>

Basic commands
- CREATE
- READ
- UPDATE
- DELETE
- (items in the script that are changable, like table name, are typed in small caps)
<br><br><br><br>
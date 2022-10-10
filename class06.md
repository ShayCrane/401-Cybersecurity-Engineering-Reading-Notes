Reading Notes <br>
Class 06<br>
Re: Enterprise File Transfers; Hashing <br><br><br><br>

*The purpose of this document is to facilitate my learning of various cybersecurity topics.  It is created for my personal use, and is a summary, including paraphrasing and direct quotes, of information found in the article(s) linked within.*<br><br>
## Applying the CIA Triad to Enterprise File Transfer
*https://www.jscape.com/blog/implementing-the-cia-triad-when-transferring-files-through-the-internet*
<br><br>
### Achieving security in enterprise file transfers
**Confidentiality**: 
- file transfers require both types of encryption: 
    - data at rest
        - SSH or SSL (e.g. FTPS, HTTPS, WebDAVs) 
    - data in transit
        - disk-or-file-level encryption solutions, like OpenPGP 
        - authentication, 2-factor


<br><br>
**Integrity**
- hash functions
- digital signatures
    - secure file transfer protocols (e.g. FTPS, HTTPS, WebDAVs)


<br><br>
**Avialability**
- set up a high availability (HA) cluster: 
    1. set up one or more failover servers (active-passive HA configuration)

**or**
    2. set up two or more active servers (active-active HA configuration)
    - distributes workload and minimizes chance of server going down; redundant

<br><br>
***But you need to apply all three, and the best way to go about this is to find a service solution that incorporates all three elements of the CIA triad, such as the services that are linked within the original article.  A configuration like this is complex to do from scratch.***

<br><br>
## What Are MD5, SHA-1, and SHA-256 Hashes, and How Do I Check Them?
* https://www.howtogeek.com/67241/htg-explains-what-are-md5-sha-1-hashes-and-how-do-i-check-them/*


<br><br>
### Hashes: <br><br>
**Types of hash functions**:
1. MD5; 
2. SHA-1; and
3. SHA-256 (most secure). 
<br><br>
**What are they?**
- products of cryptographic algorithms that cipher the information being hashed into a string of characters that is always of the same length regardless of the input to be hashed. 

<br><br><br><br>
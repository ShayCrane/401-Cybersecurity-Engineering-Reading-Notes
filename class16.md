Reading Notes <br>
Class 16<br>
Re: Cloud Identity and Access Management (AWS)<br><br><br><br>

*The purpose of this document is to facilitate my learning of various cybersecurity topics.  It is created for my personal use, and is a summary, including paraphrasing and direct quotes, of information found in the article(s) linked within.*<br><br>

## Anatomy of a Cloud Breach: How 100 Million Credit Card Numbers Were Exposed
*https://www.zscaler.com/resources/white-papers/capital-one-data-breach.pdf*
<br><br><br>

**An attacker gained access to the financial institution's data, resulting in a data breach of approximately 100 million customers' PII**<br><br>

*"The attacker identified a misconfigured WAF that enabled accessing the corresponding AWS EC2 instance/ ECS task metadata using Server-side Request Forgery (SSRF) and call the metadata service endpoint using"*<br><br>

- Then the attacker used the role name to gain access to temporary credentials. 
- The attacker then gained access to the S3 buckets 
<br><br>

***This attack is much the same as our recent lab using splunk***
<br><br>

**The article gives a full list of recommendations for AWS Governance Practices that would prevent attacks like this**

<br><br><br><br>



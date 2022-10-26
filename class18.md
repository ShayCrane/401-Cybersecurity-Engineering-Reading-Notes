Reading Notes <br>
Class 18<br>
Re: Intro to AWS CLoudWatch<br><br><br><br>

*The purpose of this document is to facilitate my learning of various cybersecurity topics.  It is created for my personal use, and is a summary, including paraphrasing and direct quotes, of information found in the article(s) linked within.*<br><br>

## Introduction to AWS CloudWatch
*https://www.citrusconsulting.com/introduction-to-aws-cloudwatch/*
<br><br><br>

**CloudWatch Events**
- allows monitoring of almost real-time events through CloudWatch Logs
    - can be configured to trigger notifications through a multitude of services, AWS or otherwise 
    - CloudWatch Alarm
<br><br>
**Rules**
- routes matching events to configured targets or processing in no particular order
<br><br>
**Targets**
- specified within rules
<br><br>

**CloudWatch Logs** 
- can be sent to a centralized account for audit and analysis
<br><br>

**CloudWatch Anomaly Detection**
- capabilities include: 
    - learn and model expected behavior of a metric based on prior data
    - calculate expected values, generates a band from this info
    - creation of alarms based on the band, remediation
    - AWS API & CloudFormation support
<br><br><br><br>
Reading Notes <br>
Class 02<br>
Re: AWS Architecture, SOC2<br><br><br><br>

*The purpose of this document is to facilitate my learning of various cybersecurity engineering topics and tools.  It is created for my personal use, and is a summary, including paraphrasing and direct quotes, of information found in the article(s) linked within.*<br><br>

## Compute Abstractions on AWS: A Visual Story
*https://aws.amazon.com/blogs/architecture/compute-abstractions-on-aws-a-visual-story/*<br><br>

In this blog entry, the author, who is an AWS employee, offers us an introduction to some of the different levels of "compute abstractions" introduced to the industry over the last couple of decades.<br><br>
Separation of duties:  divides responsibilities in a manner which varies depending on the service.   
1.  The instance/virtual machine abstraction (Amazon Elastic Compute Cloud, including Lightsail)<br>
customers: the vm guest os and above, and its lifecycle.  
    - AWS: manages hardware and hypervisor and their lifecycles.<br><br>

2.  The container abstraction (Docker, Amazon Elastic Container Service vanilla and for Kubernetes, or EKS for container control planes. <br>

    - control plane: exposing API interface to define, deploy, and lifecycle containers; AWS handles installation, operation, and scale of your cluster mngmt infrastructure.<br>
    - data plane: providing CPU/Memory/Network/Storage (capacity to run and connect to a network); AWS manages ECS or EKS.  <br><br>

3.  The function abstraction:  AWS  manages the infrastructure under your function. <br><br>

4.  The bare metal abstraction:  allows user to provision bare metal instances. <br><br>

5.  The full container abstraction:  all the above together (AWS Fargate).
    - AWS has responsibility over containers data plane.<br><br><br><br>
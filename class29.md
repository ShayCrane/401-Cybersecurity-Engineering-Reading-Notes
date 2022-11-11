Reading Notes <br>
Class 29<br>
Re:Threat Modeling; STRIDE <br><br><br>

*The purpose of this document is to facilitate my learning of various cybersecurity topics.  It is created for my personal use, and is a summary, including paraphrasing and direct quotes, of information found in the article(s) linked within.*<br><br>

## Threat Modeling
https://owasp.org/www-community/Threat_Modeling


A threat model is an overview of an application or system environment used to understand threats and design mitigations against them, thereby improving security. 

Threat models typically include the following: 
- Description of the subject to be modeled
- Assumptions that can be checked or challenged in the future as the threat - - landscape changes
- Potential threats to the system
- Actions that can be taken to mitigate each threat
- A way of validating the model and threats, and verification of success of actions taken

Four Questions Framework: 
- What are we working on?
- What can go wrong?
- What are we going to do about it?
- Did we do a good job?

To keep the model process focused, consider these points:
- Assess Scope - What are we working on? This might be as small as a sprint, or as large as a whole system.
- Identify what can go wrong - This can be as simple as a brainstorm, or as structured as using STRIDE, Kill Chains, or Attack Trees.
- Identify countermeasures or manage risk - Decide what you’re going to do about each threat. That might be to implement a mitigation, or to apply the accept/transfer/eliminate approaches of risk management.
- Assess your work - Did you do a good enough job for the system at hand?
<br><br><br><br>

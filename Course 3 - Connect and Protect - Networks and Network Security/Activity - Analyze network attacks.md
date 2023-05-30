# Activity Overview

In this activity, you will consider a scenario involving a customer of the company that you work for who experiences a security issue when accessing the company’s website. You will  identify the likely cause of the service interruption. Then, you will explain how the attack occurred and the negative impact it had on the website. 

In this course, you have learned about several common network attacks. You have learned their names, how they are carried out, and the characteristics of each attack from the perspective of the target. Understanding how attacks impact a network will help you troubleshoot issues on your organization’s network. It will also help you take steps to mitigate damage and protect a network from future attacks.

Be sure to complete this activity before moving on. The next course item will provide you with a completed exemplar to compare to your own work. You will not be able to access the exemplar until you have completed this activity.

## Scenario

Review the following scenario. Then complete the step-by-step instructions.

You work as a security analyst for a travel agency that advertises sales and promotions on the company’s website. The employees of the company regularly access the company’s sales webpage to search for vacation packages their customers might like. 

One afternoon, you receive an automated alert from your monitoring system indicating a problem with the web server. You attempt to visit the company’s website, but you receive a connection timeout error message in your browser.

You use a packet sniffer to capture data packets in transit to and from the web server. You notice a large number of TCP SYN requests coming from an unfamiliar IP address. The web server appears to be overwhelmed by the volume of incoming traffic and is losing its ability to respond to the abnormally large number of SYN requests. You suspect the server is under attack by a malicious actor. 

You take the server offline temporarily so that the machine can recover and return to a normal operating status. You also configure the company’s firewall to block the IP address that was sending the abnormal number of SYN requests. You know that your IP blocking solution won’t last long, as an attacker can spoof other IP addresses to get around this block. You need to alert your manager about this problem quickly and discuss the next steps to stop this attacker and prevent this problem from happening again. You will need to be prepared to tell your boss about the type of attack you discovered and how it was affecting the web server and employees.

## Step-By-Step Instructions

Follow the instructions and answer the question to complete the activity. Then, go to the next course item to compare your work to a completed exemplar.

### Step 1: Access the template
To use the template for this course item, click the link below and select Use Template. 

Link to template: [Cybersecurity incident report](https://docs.google.com/document/d/16SBz7S5p4k0XPP67QvkIBprKNx82Deh7sBiTA91RfzE/template/preview?usp=sharing)

### Step 2: Access supporting materials

The following supporting materials will help you complete this activity. Keep them open as you proceed to the next steps. 

To use the supporting materials for this course item, click the following links and select *Use Template*. 

Links to supporting materials: 

- [Wireshark TCP/HTTP log](https://docs.google.com/spreadsheets/d/1PGqx7XkiAq2m5147FqyZ06JhLyrprZ0mQvwBBk8vJ_I/template/preview?usp=sharing)

- [How to read the Wireshark TCP/HTTP log](https://docs.google.com/document/d/1jzwb8r-0DdJGIu4FutnGoxVJnUJ6Go9hCg3VEcRy-4Y/template/preview?usp=sharing)

### Step 3: Identify the type of attack causing this network interuption

Reflect on the types of network intrusion attacks that you have learned about in this course so far. As a security analyst, identifying the type of network attack based on the incident is the first step to managing the attack and preventing similar attacks in the future. 

Here are some questions to consider when determining what type of attack occurred: 

- What do you currently understand about network attacks?

- Which type of attack would likely result in the symptoms described in the scenario? 

- What is the difference between a denial of service (DoS) and distributed denial of service (DDoS)? 

- Why is the website taking a long time to load and reporting a connection timeout error?

Review the linked Wireshark log file excerpt and try to identify patterns in the logged network traffic. Analyze the patterns to determine which type of network attack occurred. Write your analysis in section one of the Cybersecurity incident report template provided. Describe your analysis and include the type of attack and what information led you to your decision.

### Step 4: Explain how the attack is causing the website to malfunction

Pro Tip: Save the template
You can save a blank copy of the template you used to complete this activity for further practice or in your professional projects. These templates will help you work through your thought processes and demonstrate your experience to potential employers.

### What to Include in Your Response

Be sure to address the following in your completed activity: 

- The name of the network intrusion attack

- A description of how the attack negatively impacts network performance

---

# Activity Exemplar: Analyze network attacks
Here is a completed exemplar along with an explanation of how the exemplar fulfills the expectations for the activity. 

## Completed Exemplar

To review the exemplar for this course item, click the following link and select Use Template. 

[Cybersecurity incident report exemplar](https://docs.google.com/document/d/1C_ICKNkoAsmNn4KWkRxxI-us5ZbQPi2S2adqQMkVfG0/template/preview?usp=sharing&resourcekey=0-cmePZ54ThyxJW_YBip9mOA)

## Assessment of Exemplar

Compare the exemplar to your completed activity. Review your work using each of the criteria in the exemplar. What did you do well? Where can you improve? Use your answers to these questions to guide you as you continue to progress through the course. 

**Note:** *The exemplar represents one possible explanation for the issues that the user is facing. Yours will likely differ in certain ways. What’s important is that you identified the network protocols involved and created a report. In your role as a security analyst, you and your team would make a best guess about what happened and then investigate further to troubleshoot the issue and strengthen the overall security of your network.*


The exemplar identifies that the connection timeout message is a result of a DoS attack. In this instance, the specific DoS attack is a SYN flood attack. 

To determine this, analyze the data presented in the log file excerpt attached to this activity. Next, reflect on your current understanding of network attacks to identify what type of attack is occurring based on the data available.

After identifying a possible network attack type, proceed to explain how we came to identify the attack. Then, document how this specific type of attack might have affected the network and include a general description of how the attacker exploited the network vulnerability. 

Lastly, describe how this attack resulted in the webpage displaying the connection timeout error.

The exemplar only provides one example of an explanation for the event. Describing an event typically requires presenting your evidence and explaining how you came to your decision. All patterns you notice in the logs and data are critical in determining the source and the type of network attack. The more practice you have identifying these patterns, the easier it will be to spot network attacks as they are occurring. This will allow you to respond to incidents more quickly and efficiently.
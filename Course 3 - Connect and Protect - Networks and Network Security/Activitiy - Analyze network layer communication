# Activity Overview

![line](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/7575VRkfR42-7Xv1WSugQg_1e7fbf6b48534623bf908a7c50c56df1_image.png?expiry=1685491200000&hmac=aMfCTXB3patW0VL0BnHIOCHHdyFx6wRcfEngtzID-dE)

In this activity, you will analyze DNS and ICMP traffic in transit using data from a network protocol analyzer tool. You will identify which network protocol was utilized in assessment of the cybersecurity incident. 

In the internet layer of the TCP/IP model, the IP formats data packets into IP datagrams. The information provided in the datagram of an IP packet can provide security analysts with insight into suspicious data packets in transit.

Knowing how to identify potentially malicious traffic on a network can help cybersecurity analysts assess security risks on a network and reinforce network security.

Be sure to complete this activity before moving on. The next course item will provide you with a completed exemplar to compare to your own work. You will not be able to access the exemplar until you have completed this activity. 

## Scenario

![line](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/oWLqT0BQR02lq2BsMbaiCA_ade0719eb03145d3a6627bf5a458cbf1_image.png?expiry=1685491200000&hmac=b0ZIUAV0xdWCOT4pgdqFCBAEALs30lY33VW0vJpPk14)

Review the scenario below. Then complete the step-by-step instructions.

You are a cybersecurity analyst working at a company that specializes in providing IT consultant services. Several customers contacted your company to report that they were not able to access the company website www.yummyrecipesforme.com, and saw the error “destination port unreachable” after waiting for the page to load. 

You are tasked with analyzing the situation and determining which network protocol was affected during this incident. To start, you visit the website and you also receive the error “destination port unreachable.” Next, you load your network analyzer tool, tcpdump, and load the webpage again. This time, you receive a lot of packets in your network analyzer. The analyzer shows that when you send UDP packets and receive an ICMP response returned to your host, the results contain an error message: “udp port 53 unreachable.” 

In the DNS and ICMP log, you find the following information:

1. In the first two lines of the log file, you see the initial outgoing request from your computer to the DNS server requesting the IP address of yummyrecipesforme.com. This request is sent in a UDP packet.

2. Next you find timestamps that indicate when the event happened. In the log, this is the first sequence of numbers displayed. For example: 13:24:32.192571. This displays the time 1:24 p.m., 32.192571 seconds.

3. The source and destination IP address is next. In the error log, this information is displayed as: 192.51.100.15.52444 > 203.0.113.2.domain. The IP address to the left of the greater than (>) symbol is the source address. In this example, the source is your computer’s IP address. The IP address to the right of the greater than (>) symbol is the destination IP address. In this case, it is the IP address for the DNS server: 233.18.9.101.domain

4. The second and third lines of the log show the response to your initial ICMP request packet. In this case, the ICMP 203.0.113.2 line is the start of the error message indicating that the ICMP packet was undeliverable to the port of the DNS server.

5. Next are the protocol and port number, which displays which protocol was used to handle communications and which port it was delivered to. In the error log, this appears as: udp port 53 unreachable. This means that the UDP protocol was used to request a domain name resolution using the address of the DNS server over port 53. Port 53, which aligns to the .domain extension in 203.0.113.2.domain, is a well-known port for DNS service. The word “unreachable” in the message indicates the message did not go through to the DNS server. Your browser was not able to obtain the IP address for yummyrecipesforme.com, which it needs to access the website because no service was listening on the receiving DNS port as indicated by the ICMP error message “udp port 53 unreachable.”

6. The remaining lines in the log indicate that ICMP packets were sent two more times, but the same delivery error was received both times. 

Now that you have captured data packets using a network analyzer tool, it is your job to identify which network protocol and service were impacted by this incident. Then, you will need to write a follow-up report. 

As an analyst, you can inspect network traffic and network data to determine what is causing network-related issues during cybersecurity incidents. Later in this course, you will demonstrate how to manage and resolve incidents. For now, you only need to analyze the situation. 

This incident, in the meantime, is being handled by security engineers after you and other analysts have reported the issue to your direct supervisor. 

## Step-By-Step Instructions

Follow the instructions and answer the question below to complete the activity. Then, go to the next course item to compare your work to a completed exemplar.

## Step 1: Access the template
To use the template for this course item, click the link below and select Use Template. 

Link to template:

 [Cybersecurity incident report template](https://docs.google.com/document/d/1hwjSRYalxGd-qyRIXWz8LBVuSAgEq0AHXOF_BB7DdrI/template/preview?usp=sharing)

## Step 2: Access supporting materials  
The following supporting materials will help you complete this activity. Keep them open as you proceed to the next steps. 

To use the supporting materials for this course item,  click the following links and select Use Template. 

Link to supporting materials: 

- [DNS and ICMP log](https://docs.google.com/document/d/1xHqijdYZYv7_25dESR4PInJz4d2nmWKCtjUWRIJiiuw/template/preview?usp=sharing)

- [Example of a Cybersecurity Incident Report](https://docs.google.com/document/d/118uxoizhGhxShAUvxQLQaEOlC8GcZK271x6M1ulg1bM/template/preview?usp=sharing)

## Step 3: Provide a summary of the problem found in the DNS and ICMP traffic log
The network traffic analyzer tool inspects all IP packets traveling through the network interfaces of the machine it runs on. Network packets are recorded into a file. After analyzing the data presented to you from the DNS and ICMP traffic log, identify trends in the data. Assess which protocol is producing the error message when resolving the URL with the DNS server for the yummyrecipesforme.com website. Recall that one of the ports that is displayed repeatedly is port 53, commonly used for DNS. In your analysis:  

- Include a brief summary of the DNS and ICMP log analysis and identify which protocol was used for the ICMP traffic.

- Provide a few details about what was indicated in the logs.

- Interpret the issues found in the logs.

Record your responses in part one of the cybersecurity incident report.  

## Step 4: Explain your analysis of the data and provide one solution to implement 
Now that you’ve inspected the traffic log and identified trends in the traffic, describe why the error messages appeared on the log. Use your answer in the previous step and the scenario to identify the reason behind the ICMP error messages. The error messages indicate that there is an issue with a specific port. What do the different protocols involved in the log reveal about the incident? In your response:

- State when the problem was first reported.

- Provide the scenario, events, and symptoms identified when the event was first reported.  

- Describe the information discovered while investigating the issue up to this point.

- Explain the current status of the issue.

- Provide the suspected root cause of the problem.

- List the next steps needed to troubleshoot and resolve the issue.

Record your responses in part two of the cybersecurity incident report. 

## Pro tip: Save the template
Finally, be sure to save a blank copy of the template you used to complete this activity. You can use it for further practice or in your professional projects. These templates will help you work through your thought processes and demonstrate your experience to potential employers.

### What to Include in Your Response
Be sure to address the following items in your completed activity:   

- Provide a summary of the problem found in the DNS and ICMP traffic log

- Explain your analysis of the data and provide one solution to implement 

---

# Activity Exemplar: Analyze network layer communication
Here is a completed exemplar along with an explanation of how the exemplar fulfills the expectations for the activity. 

## Completed Exemplar

To review the exemplar for this course item, click the following links and select Use Template. 

[Cybersecurity incident report exemplar](https://docs.google.com/document/d/1eTO28_1HfJWelqyw_bWgcYdXu4JfMneJSLpd1CTOGyM/template/preview?usp=sharing)

[Cybersecurity incident report exemplar explained](https://docs.google.com/document/d/1GZixC7LMbiDlngl-8zCJjoi0xSQawbEVUBmzDoZJ6Kw/template/preview?usp=sharing)

## Assessment of Exemplar

Compare the exemplar to your completed activity. Review your work using each of the criteria in the exemplar. What did you do well? Where can you improve? Use your answers to these questions to guide you as you continue to progress through the course. 

**Note:** The exemplar offers one possible approach to investigating and analyzing a possible security event. In your role as a security analyst, you and your team would make a best guess about what happened and then investigate further to troubleshoot the issue and strengthen the overall security of your network.



Writing an effective cybersecurity analysis report can help troubleshoot network issues and vulnerabilities more quickly and effectively. The more practice you have analyzing network traffic for suspicious trends and activity, the more effective you and your team will be at managing and responding to risks that are present on your network. 

### Key takeaways
As a security analyst, you may not always know exactly what is at the root of a network issue or a possible attack. But being able to analyze the IP packets involved will help you make a best guess about what happened or potentially prevent an attack from invading the network. The network protocol and traffic logs will become the starting point for investigating the issue further and addressing the attack.
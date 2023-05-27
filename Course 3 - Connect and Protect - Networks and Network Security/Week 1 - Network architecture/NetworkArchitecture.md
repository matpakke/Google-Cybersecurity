# Network components, devices, and diagrams
In this section of the course, you will learn about network architecture. 

Once you have a foundational understanding of network architecture, sometimes referred to as network design, you will learn about security vulnerabilities inherent in all networks and how malicious actors attempt to exploit them. In this reading, you will review network devices and connections and investigate a simple network diagram similar to those used every day by network security professionals. Essential tasks of a security analyst include setting up the tools, devices, and protocols used to observe and secure network traffic. 

## Devices on a network 
Network devices are the devices that maintain information and services for users of a network. These devices connect over wired and wireless connections. After establishing a connection to the network, the devices send data packets. The data packets provide information about the source and the destination of the data.

![A network diagram displaying how different devices are connected to an internal network](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/URorDIh9TNiq7e481RWHmQ_85911828bd7c43b38761dd2b520e8df1_CS_R-041_-Edited-S34G001-1-.png?expiry=1685318400000&hmac=OAHQnY_WQso06ci2W6younfrpkzhSIp4hxQZqOLURNA)

### Devices and desktop computers 
Most internet users are familiar with everyday devices, such as personal computers, laptops, mobile phones, and tablets. Each device and desktop computer has a unique MAC address and IP address, which identify it on the network, and a network interface that sends and receives data packets. These devices can connect to the network via a hard wire or a wireless connection.

### Firewalls
A **firewall** is a network security device that monitors traffic to or from your network. Firewalls can also restrict specific incoming and outgoing network traffic. The organization configures the security rules. Firewalls often reside between the secured and controlled internal network and the untrusted network resources outside the organization, such as the internet.

### Servers
Servers provide a service for other devices on the network. The devices that connect to a server are called clients. The following graphic outlines this model, which is called the client-server model. In this model, clients send requests to the server for information and services. The server performs the requests for the clients. Common examples include DNS servers that perform domain name lookups for internet sites, file servers that store and retrieve files from a database, and corporate mail servers that organize mail for a company. 

![A client server model showing three client devices sending requests and receiving responses from a database server.](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/FI4hBJhWTEyWNXoKI9EgsA_5a3867623fe5482aa3cb88b2e17fd3f1_m11tx1zMlcjG_2VzVR5QC6doDnVW9U6b0n04lmDZCi1BdjEjt-owNV78CEYLQeX_OoblVT1iYfESmwKKY7KkWUA-CB_bQXn--BroYC9c6GVbiZT1DJimU5CCOfNOz8HTQJUVivm8pNKK7NHRzv3W9INsegVffLpT23LJ2sXvgAdmHUwchtuJksNQwLqw70E?expiry=1685318400000&hmac=D7j0yXswY-XCKqLVND-VDd5aDBc2mfQXLmX3HiFhMDc)

### Hubs and switches
Hubs and switches both direct traffic on a local network. A hub is a device that provides a common point of connection for all devices directly connected to it. Hubs additionally repeat all information out to all ports. From a security perspective, this makes hubs vulnerable to eavesdropping. For this reason, hubs are not used as often on modern networks; most organizations use switches instead. 

A switch forwards packets between devices directly connected to it. It maintains a MAC address table that matches MAC addresses of devices on the network to port numbers on the switch and forwards incoming data packets according to the destination MAC address. Switches are a part of the data link layer in the TCP/IP model.

### Routers
Routers sit between networks and direct traffic, based on the IP address of the destination network. In the TCP/IP model, routers are a part of the network layer. The IP address of the destination network is contained in the IP header. The router reads the header information and forwards the packet to the next router on the path to the destination. This continues until the packet reaches the destination network. Routers can also include a firewall feature that allows or blocks incoming traffic based on information in the transmission. This stops malicious traffic from entering the private network and damaging the local area network. 

## Modems and wireless access points
### Modems

Modems usually interface with an internet service provider (ISP). ISPs provide internet connectivity via telephone lines or coaxial cables. Modems receive transmissions from the internet and translate them into digital signals that can be understood by the devices on the network. Usually, modems connect to a router that takes the decoded transmissions and sends them on to the local network. 

**Note:** Enterprise networks used by large organizations to connect their users and devices often use other broadband technologies to handle high-volume traffic, instead of using a modem. 

![A modem converting data from the internet, connecting to a Wi-Fi router](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/5cpm9ICmSJCX3MLFfqT6kw_a636fcf868104322ad316bc98fabc3f1_S34G002.png?expiry=1685318400000&hmac=U6In6UdnX6EK4DzdGaYp0Y0Yvus7yz-MuUIhroJKJSY)

### Wireless access point

A wireless access point sends and receives digital signals over radio waves creating a wireless network. Devices with wireless adapters connect to the access point using Wi-Fi. Wi-Fi refers to a set of standards that are used by network devices to communicate wirelessly. Wireless access points and the devices connected to them use Wi-Fi protocols to send data through radio waves where they are sent to routers and switches and directed along the path to their final destination.

![A wireless access point connected to wired and wireless devices on a network](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/dI_SIruhQeuOZZVnzI6fmA_36c5e1379c0f4990a6fe0ac0c27763f1_S34G003.png?expiry=1685318400000&hmac=YurTW70PeqiDpOAWu819l5qnp16Uddm63b1TijCbxPg)

### Using network diagrams as a security analyst
Network diagrams allow network administrators and security personnel to imagine the architecture and design of their organization’s private network.

Network diagrams are topographical maps that show the devices on the network and how they connect. Network diagrams use small representative graphics to portray each network device and dotted lines to show how each device connects to the other. Security analysts use network diagrams to learn about network architecture and how to design networks. 

![A router connecting to two firewalls and creating two separate security zones](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/tj5DFJGVQDuBAxqnZ_AL2w_418d88f79e794c3082881500887fa7f1_CS_R-041_-Edited-S34G004.png?expiry=1685318400000&hmac=0OSR1X-uE-e9IatHgSXK2QY8-ubnT65Brl0CGe-rQvU)

### Key takeaways
In the client-server model, the client requests information and services from the server, and the server performs the requests for the clients. Network devices include routers, workstations, servers, hubs, switches, and modems. Security analysts use network diagrams to visualize network architecture.

----

# Cloud computing and software-defined networks
In this section of the course, you’ve been learning the basic architecture of networks. You’ve learned about how physical network devices like workstations, servers, routers, and switches connect to each other to create a network. Networks may cover small geographical areas, as is the case in a local area network (LAN). Or they may span a large geographic area, like a city, state, or country, as is the case in a wide area network (WAN). You also learned about cloud networks and how cloud computing has grown in recent years.

In this reading, you will further examine the concepts of cloud computing and cloud networking. You’ll learn about software-defined networks, virtualization tools, and the difference between a cloud server and a web server. This reading will also cover the benefits of hosting networks in the cloud and why cloud-hosting is beneficial for large organizations.

## Computing processes in the cloud
Traditional networks are called on-premise networks, which means that all of the devices used for network operations are kept at a physical location owned by the company, like in an office building, for example. **Cloud computing**, however, refers to the practice of using remote servers, applications, and network services that are hosted on the internet instead of at a physical location owned by the company.

A cloud service provider (CSP) is a company that offers cloud computing services. These companies own large data centers in locations around the globe that house millions of servers. Data centers provide technology services, such as storage, and compute at such a large scale that they can sell their services to other companies for a fee. Companies can pay for the storage and services they need and consume them through the CSP’s application programming interface (API) or web console.

CSPs provide three main categories of services:

- **Software as a service (SaaS)** refers to software suites operated by the CSP that a company can use remotely without hosting the software. 

- **Infrastructure as a service (Iaas)** refers to the use of virtual computer components offered by the CSP. These include virtual containers and storage that are configured remotely through the CSP’s API or web console. Cloud-compute and storage services can be used to operate existing applications and other technology workloads without significant modifications. Existing applications can be modified to take advantage of the availability, performance, and security features that are unique to cloud provider services.

- **Platform as a service (PaaS)** refers to tools that application developers can use to design custom applications for their company. Custom applications are designed and accessed in the cloud and used for a company’s specific business needs.

![Differences between IaaS, PaaS, and SaaS and how each connects to a physical data center.](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/oFV1OH67RJOjAed1pXzAuw_6b34b3019d4d448b9c662ebb39970df1_CS_R-042_iass-paas-and-saas.png?expiry=1685318400000&hmac=XHdt7a3kteCD2DcKRmzajYdL4_IQjJTccDx9mA6di74)

## Hybrid cloud environments
When organizations use a CSP’s services in addition to their on-premise computers, networks, and storage, it is referred to as a hybrid cloud environment. When organizations use more than one CSP, it is called a multi-cloud environment. The vast majority of organizations use hybrid cloud environments to reduce costs and maintain control over network resources.

## Software-defined networks
CSPs offer networking tools similar to the physical devices that you have learned about in this section of the course. Next, you’ll review  software-defined networking in the cloud. Software-defined networks (SDNs) are made up of virtual network devices and services. Just like CSPs provide virtual computers, many SDNs also provide virtual switches, routers, firewalls, and more. Most modern network hardware devices also support network virtualization and software-defined networking. This means that physical switches and routers use software to perform packet routing. In the case of cloud networking, the SDN tools are hosted on servers located at the CSP’s data center.

## Benefits of cloud computing and software-defined networks 
Three of the main reasons that cloud computing is so attractive to businesses are reliability, decreased cost, and increased scalability. 

### Reliability
Reliability in cloud computing is based on how available cloud services and resources are, how secure connections are, and how often the services are effectively running. Cloud computing allows employees and customers to access the resources they need consistently and with minimal interruption. 

### Cost
Traditionally, companies have had to provide their own network infrastructure, at least for internet connections. This meant there could be potentially significant upfront costs for companies. However, because CSPs have such large data centers, they are able to offer virtual devices and services at a fraction of the cost required for companies to install, patch, upgrade, and manage the components and software themselves.

### Scalability
Another challenge that companies face with traditional computing is scalability. When organizations experience an increase in their business needs, they might be forced to buy more equipment and software to keep up. But what if business decreases shortly after? They might no longer have the business to justify the cost incurred by the upgraded components. CSPs reduce this risk by making it easy to consume services in an elastic utility model as needed. This means that companies only pay for what they need when they need it. 

Changes can be made quickly through the CSPs, APIs, or web console—much more quickly than if network technicians had to purchase their own hardware and set it up. For example, if a company needs to protect against a threat to their network, web application firewalls (WAFs), intrusion detection/protection systems (IDS/IPS), or L3/L4 firewalls can be configured quickly whenever necessary, leading to better network performance and security.

## Key takeaways
In this reading, you learned more about cloud computing and cloud networking. You learned that CSPs are companies that own large data centers that house millions of servers in locations all over the globe and then provide modern technology services, including compute, storage, and networking, through the internet. SDNs are an approach to network management. SDNs enable dynamic, programmatically efficient network configurations to improve network performance and monitoring. This makes it more like cloud computing than traditional network management. Organizations can improve reliability, save costs, and scale quickly by using CSPs to provide networking services instead of building and maintaining their own network infrastructure. 

### Resources for more information
For more information about cloud computing and the services offered, you can review [Google Cloud (GC)](https://cloud.google.com/).
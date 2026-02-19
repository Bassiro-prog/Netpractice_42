*This project has been created as part of the 42 curriculum by bnanque*

# NetPractice

## Description

NetPractice is a networking training project designed to help students understand how computer networks actually work in practice.

The goal of this project is to configure different network scenarios by correctly setting IP addresses, subnet masks, and routing paths so that hosts can communicate with each other and access the Internet when required.

At first, the levels seem simple, but they gradually become more complex. This project forced me to truly understand how IP ranges work, how subnet masks divide networks, and how routers decide where to send packets. Instead of memorizing theory, I had to apply it in real configurations.

Through this project, I worked with concepts such as:

- TCP/IP addressing  
- Subnet masks  
- Default gateway  
- Routers and switches  
- Network segmentation  
- OSI layers  
- Basic routing logic  

Each level required careful analysis of network boundaries, valid host ranges, and communication paths.

---

## Instructions

### Running the training interface

1. Download the NetPractice project from the 42 platform.
2. Open the file `index.html` in your web browser.
3. Enter your 42 login (or start directly if allowed).
4. Select a level and configure the network.
5. Adjust IP addresses, subnet masks, and gateways until all goals are validated.

When a level is successfully completed, a button appears allowing you to move to the next level.

---

### Exporting configurations

After completing each level:

- Before moving to the next level, export your configuration using the **"Get my config"** button.
- A configuration file will be downloaded.
- Do not modify the content of the exported file.
- Place the file at the root of your Git repository.

---

## Networking Concepts Studied

During this project, I studied and applied several core networking concepts:

### TCP/IP Addressing
Understanding how devices are identified in a network and how communication works between different networks.

### Subnet Mask
Learning how subnet masks define the network portion and the host portion of an IP address, and how they create subnet boundaries.

### Default Gateway
Understanding how a device sends traffic outside its local network through a router.

### Routers and Switches
- Switches connect devices inside the same local network.
- Routers connect different networks and forward packets between them.

### OSI Model
Reviewing how data moves through different layers (from application to physical layer) and how each layer has a specific role in communication.

---

## My Approach

For each level, I first identify how many different networks are present in the diagram.

By counting the number of networks before configuring anything, I can:

- Divide IP ranges correctly  
- Choose appropriate subnet masks  
- Avoid overlapping networks  
- Determine valid host ranges quickly  
- Understand where routers are required  

After that, I:

- Identify network addresses  
- Calculate broadcast addresses  
- Verify subnet consistency  
- Ensure routing paths are logically correct  

When communication fails, I analyze whether the issue is caused by:

- An incorrect subnet mask  
- An invalid IP address  
- A missing or incorrect default gateway  
- A routing inconsistency  

This approach helped me solve levels more efficiently and logically instead of guessing configurations.

---

## Resources

To better understand the networking concepts required for this project, I used the following resources:

- Cisco Networking Basics  
  https://www.cisco.com/c/en/us/solutions/small-business/resource-center/networking/networking-basics.html  

- TCP/IP Guide  
  http://www.tcpipguide.com/  

- OSI Model explanation  
  https://www.cloudflare.com/learning/ddos/glossary/open-systems-interconnection-model-osi/  

- Subnetting practice and explanations  
  https://www.subnetting.net/  

- https://youtu.be/HQUw0CfQWAM?si=MaLYcH11nZqkD31Z

These resources helped reinforce my understanding of:

- TCP/IP addressing  
- Subnet masks  
- Default gateway  
- Routers  
- Switches  
- OSI layers  
- Network segmentation  

### AI Usage

ChatGPT was used as a support tool to clarify subnetting logic, routing behavior, and to review networking concepts when I had doubts.  

It was also used to help structure this README file in a clear and professional way.

All configurations and problem-solving were personally understood and implemented.

---

## Conclusion

NetPractice helped me build a solid foundation in networking. It improved my logical thinking when analyzing network problems and strengthened my understanding of how real network communication works.

This project bridges the gap between networking theory and practical configuration.

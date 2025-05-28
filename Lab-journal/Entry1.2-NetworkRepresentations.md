# Entry 1.2 – Network Representations (Packet Tracer)

This lab introduced a simplified business network using Packet Tracer’s Logical mode. It was designed to help me identify different network components, compare LANs and WANs, and think critically about how topology shapes communication. I explored freely and completed the guided questions.

---

## Screenshots

**Full Logical Topology**

![Logical Topology Overview](../screenshots/Entry1.2.1Screenshot.png)

## Part 1: Identifying Network Components and Media

### **Q: What are the intermediary device categories?**  
Routers, switches, modems, access points, and cloud interfaces.

### **Q: How many end devices are in the topology (only one connection)?**  
15

### **Q: How many intermediary devices (multiple connections, not counting clouds)?**  
13

### **Q: How many end devices are not desktop computers?**  
9 — including servers, printers, smartphones, tablets, IP phones.

### **Q: How many different types of media are used?**  
4 types:  
- Coaxial (blue)  
- Serial DTE (red)  
- Copper straight-through (green)  
- Wireless (dashed)

---

## Part 2: Purpose of Devices

### **Q: What is the client-server model?**  
A network architecture where clients (like PCs or phones) request services from a centralized server.

### **Q: List two functions of intermediary devices.**  
1. Refresh/resend signals (e.g., repeater, switch)  
2. Route traffic between networks (e.g., router)

### **Q: List two criteria for choosing a media type.**  
1. Network size (e.g., SOHO vs enterprise)  
2. Required upload/download speed

---

## Part 3: LANs vs WANs

### **Q: What’s the difference between a LAN and a WAN?**  
A LAN (Local Area Network) connects nearby devices—like a home or office.  
A WAN (Wide Area Network) connects LANs across regions, states, or even countries.  
Example: Microsoft offices connected across states = WAN.

### **Q: How many WANs in the topology?**  
1

### **Q: How many LANs?**  
3 (Home Office, Central, and Branch)

### **Q: How would you describe the internet?**  
A global collection of interconnected networks.

### **Q: How do home users typically connect to the internet?**  
Via wired or wireless router > ISP > internet backbone.

### **Q: How do businesses in your area connect?**  
Most use FIOS or DSL connections.

---

## Challenge Tasks

### **Task 1: Add an End Device**  
I added a PC to the Home Office LAN. It was limited by missing login credentials, but I confirmed it had a path to send and receive traffic via the router.  
If fully configured, it would need an IP address, gateway, and DNS server info.

### **Task 2: Add an Intermediary Device**  
I added a switch between the router and the new PC. It’s redundant in this context, but worked as a test of placement and cabling.  
If properly connected, the switch should allow the PC to communicate with the rest of the LAN.

---
**Full Network Topology After Edits**

![Detailed Topology View](../screenshots/Entry1.2.2Screenshot.png)

---

## Reflection

This lab helped me sharpen my ability to visually interpret a network. I understand now that topology isn't just about how devices look on a diagram—it's about their roles, relationships, and reach. I also appreciated the challenge prompts, which encouraged me to think creatively, test limits, and approach the network like a living system.

---

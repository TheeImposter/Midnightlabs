# Entry 1.3 – Core Network Characteristics

This entry covers the four foundational attributes every network architect must address: fault tolerance, scalability, Quality of Service (QoS), and security. Understanding these ensures that networks meet user expectations under real-world conditions.

---

## 🛠️ Fault Tolerance  
**Definition:** The ability of a network to continue operating properly in the event of a failure of one or more of its components.  
**Key Points:**  
- **Redundancy:** Duplicate critical links or devices (e.g., dual routers, switched fabrics).  
- **Packet Switching:** Breaks client data into packets that may take different paths to the same destination, reassembled at the end.  
- **Design Principle:** “No single point of failure” — every critical path should have a backup.

---

## 🚀 Scalability  
**Definition:** The capability to grow the network (more users, more applications) without degrading performance.  
**Key Points:**  
- **Horizontal Scaling:** Add more devices or links.  
- **Vertical Scaling:** Upgrade existing hardware (faster CPUs, more memory).  
- **Standards of Practice (SoPs):** Ensure purchases align with vendors’ roadmaps so you aren’t stuck with proprietary hardware that can’t expand.

---

## 🎚️ Quality of Service (QoS)  
**Definition:** Prioritization of network traffic so that critical applications maintain performance under congestion.  
**Key Points:**  
- **Unified Networks:** Voice, video, and data all share the same infrastructure.  
- **Bandwidth Management:** Policies that prioritize VoIP or video conferencing over bulk file transfers.  
- **Metrics:** Measured in bits per second (bps), jitter, latency, and packet loss thresholds.

---

## 🛡️ Security  
Two dimensions:

1. **Infrastructure Security**  
   - **Physical Controls:** Locked closets, badge-access doors for core switches and routers.  
   - **Device Hardening:** Disable unused ports, apply firmware updates, secure management interfaces.

2. **Information Security** (the “CIA Triad”)  
   - **Confidentiality:** Ensure data only reaches intended recipients (no “detours”).  
   - **Integrity:** Guarantee data isn’t altered in transit (like a sealed trailer).  
   - **Availability:** Authorized users can access services when they need them.

**Common Solutions:**  
- **SOHO Networks:** Antivirus/antispyware, basic firewall filtering.  
- **Enterprise Networks:** Dedicated next-gen firewalls, ACLs, IPS/IDS, VPN concentrators.

---

## 💬 Reflection  
These four pillars form the backbone of any resilient, high-performing network. Early on, it’s tempting to focus on speed or capacity—but without redundancy (fault tolerance) and proper prioritization (QoS), even the fastest links fail under load. Likewise, security must be baked in at every layer, or the network can’t be trusted. Logging these core concepts now lays the groundwork for the hands-on projects to come.

*Logged as part of the MidnightLabs EXP Grind 1.x series.*  

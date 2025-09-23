markdown
Copy Code
# IPv6 Self-Study Comprehensive Course

## Course Overview

This self-paced IPv6 course is designed for networking professionals, students, and enthusiasts seeking a thorough understanding of IPv6 addressing, configuration, and deployment. The course covers theoretical concepts, practical exercises, and assessment questions, referencing high-quality online resources.

---

## Table of Contents

1. Introduction to IPv6
2. IPv6 Addressing Architecture
3. IPv6 Address Types and Formats
4. IPv6 Routing
5. Transition Mechanisms from IPv4 to IPv6
6. Security in IPv6
7. Troubleshooting IPv6 Networks
8. IPv6 in Practice: Configuration Labs & Exercises

---

## Prerequisites and Skills Required

To be successful in this course, here are the prerequisites and skills required:

- **Basic Networking Concepts**: Understanding of the OSI model and TCP/IP stack. These concepts are critical for grasping how IPv6 fits into modern networks.

- **IPv4 Addressing & Subnetting**: Familiarity with IPv4 addressing principles, such as subnetting and CIDR notation, as IPv6 builds on many of these concepts.

- **Experience with Command Line Interfaces**: Knowledge of working with CLI environments such as Windows, Linux, or Cisco IOS, as this course involves configuration exercises.

- **Understanding of Networking Devices**: Experience with devices like routers, switches, and firewalls to practice IPv6 configuration in networking environments.

---

## Module Breakdown, Time Frame, and Curriculum

| Module                                           | Estimated Time      |
|--------------------------------------------------|---------------------|
| 1. Introduction to IPv6                          | 2 hours             |
| 2. IPv6 Addressing Architecture                  | 2 hours             |
| 3. IPv6 Address Types and Formats                | 2 hours             |
| 4. IPv6 Routing                                  | 3 hours             |
| 5. Transition Mechanisms from IPv4 to IPv6       | 2.5 hours           |
| 6. Security in IPv6                              | 2 hours             |
| 7. Troubleshooting IPv6 Networks                 | 2 hours             |
| 8. IPv6 in Practice: Configuration Labs & Exercises | 4 hours           |

**Total Estimated Time**: *~19.5 hours* (Self-paced)

---

## Module Content with References

### 1. Introduction to IPv6
- **Why IPv6? Address Exhaustion, Growth of Internet**
    - Explanation: IPv4 limits, public address exhaustion, IoT growth demands.
    - References:
        - [What is IPv6, why is it so important](https://softhandtech.com/why-do-we-switch-ipv4-to-ipv6/)
        - [Advantages of IPv6](https://www.geeksforgeeks.org/computer-networks/advantages-of-ipv6/)

- **Difference Between IPv4 and IPv6**
    - Explanation: Packet structure, address length, improved features.
    - References:
        - [IPv4 vs. IPv6 - What’s the difference, and which is faster?](https://www.siteground.com/kb/ipv4-vs-ipv6/)
        - [IPv4 vs IPv6: Key Differences, Benefits, and Migration Guide](https://cc-techgroup.com/ipv4-vs-ipv6/)

---

### 2. IPv6 Addressing Architecture
- **IPv6 Address Structure (128-bits, Hexadecimal, Blocks)**
    - Explanation: How IPv6 addresses are organized and represented.
    - References:
        - [IPv6 Address Types, Notation, and Structure Explained](https://www.computernetworkingnotes.com/networking-tutorials/ipv6-address-types-notation-and-structure-explained.html)
        - [IETF RFC 4291: IPv6 Addressing Architecture](https://www.rfc-editor.org/rfc/rfc4291)

- **Notation and Abbreviation Rules**
    - Explanation: Simplifying address writing using :: and omitting leading zeros.
    - References:
        - [How to Simplify Shorten and Compress IPv6 Addresses](https://www.omnisecu.com/tcpip/ipv6/how-to-simplify-ipv6-addresses.php)
        - [IPv6 Addressing Format and Conventions](https://www.geeksforgeeks.org/computer-networks/ipv6-addressing-format-and-conventions/)

---

### 3. IPv6 Address Types and Formats
- **Unicast, Anycast, Multicast**
    - Explanation: Unique address for each interface, address shared by multiple interfaces for fastest response, one-to-many communication.
    - References:
        - [Unicast, Multicast, and Anycast](https://ipv6.net/guide/mastering-ipv6-a-complete-guide-chapter-4-unicast-multicast-and-anycast-adventures/)
        - [Different IPv6 Address Types Explained](https://www.uninets.com/blog/ipv6-address-types)

- **Global, Link-local, Unique Local Addresses**
    - Explanation: Address scope, use cases.
    - References:
        - [Cisco: IPv6 Address Types]([https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/ipv6/command/ipv6-cr-book/ipv6.html](https://ipcisco.com/lesson/ipv6-address-types/))
        - [IPv6 address types](https://www.networkacademy.io/ccna/ipv6/ipv6-address-types)

---

### 4. IPv6 Routing
- **Routing Protocols (OSPFv3, RIPng, EIGRP for IPv6, BGP)**
    - Explanation: Protocol overview and differences in IPv6 environment.
    - References:
        - [How IPv6 Routing works](https://ipv6.net/guide/mastering-ipv6-a-complete-guide-chapter-7-how-ipv6-routing-works-the-internets-highway-system/)
        - [Mastering IPv6 Routing](https://itintrail.com/2025/04/28/mastering-ipv6-routing/)

- **Static Routing in IPv6**
    - Explanation: Syntax and use cases.
    - References:
        - [IPv6 Static Routing](https://www.networkacademy.io/ccna/ipv6/ipv6-static-routing)
        - [IPv6 Static Routing Configuration Made Easy With Examples](https://ccnapracticallabs.com/configure-ipv6-static-route/)

---

### 5. Transition Mechanisms from IPv4 to IPv6
- **Dual Stack, Tunnels, NAT64/DNS64**
    - Explanation: Methods allowing coexistence and transition.
    - References:
        - [IETF RFC 6144: IPv6 Transition Mechanisms](https://www.rfc-editor.org/rfc/rfc6144.html)
        - [Transition From IPv4 to IPv6 Address](https://www.geeksforgeeks.org/computer-networks/transition-from-ipv4-to-ipv6-address/)

- **Practical Examples (Packet Captures/Demos)**
    - References:
        - [Analyze IPv6 Traffic with Wireshark](https://labex.io/tutorials/wireshark-analyze-ipv6-traffic-with-wireshark-415950)
        - [Use Packet Capture to Analyze Network Traffic](https://www.juniper.net/documentation/us/en/software/junos/network-mgmt/topics/topic-map/analyze-network-traffic-by-using-packet-capture.html)

---

### 6. Security in IPv6
- **ICMPv6, Neighbor Discovery, and Security Risks**
    - Explanation: Protocol operation and vulnerabilities.
    - References:
        - [The Hidden Cybersecurity Risks of IPv6](https://teamivity.substack.com/p/the-hidden-cybersecurity-risks-of)
        - [Security Risks of IPv6 in your network](https://thwack.solarwinds.com/resources/b/geek-speak/posts/security-risks-of-ipv6-in-your-network)

- **Best Practices for IPv6 Security**
    - References:
        - [NSA IPv6 Security Guidance](https://www.nsa.gov/Press-Room/News-Highlights/Article/Article/3270451/nsa-publishes-internet-protocol-version-6-ipv6-security-guidance/)
        - [IPv6 and IoT Security Best Practices](https://hpc.mil/solution-areas/networking/ipv6-knowledge-base/ipv6-knowledge-base-security/ipv6-and-iot-security-best-practices)

---

### 7. Troubleshooting IPv6 Networks
- **Basic IPv6 Troubleshooting Commands (ping6, traceroute6, etc.)**
    - Explanation: How they differ from IPv4 tools, additional flags.
    - References:
        - [IPv6 Network Troubleshooting](https://ccnatutorials.in/ipv6-internet-protocol-version6/ipv6-network-troubleshooting/)
        - [Basic IPv6 Troubleshooting Commands](https://theinternetprotocolblog.wordpress.com/2019/11/04/basic-ipv6-troubleshooting-commands-i-ipv6-rosetta-stone-2019/)

- **Common Issues and Solutions**
    - References:
        - [How To Fix IPv6 Connectivity](https://pansift.com/blog/how-to-fix-ipv6-connectivity/)
        - [Configuring IPv4 and IPv6 Preferences in Linux Systems](https://support.tools/configure-ipv4-ipv6-preference/)

---

### 8. IPv6 in Practice: Configuration Labs & Exercises
- **Setting up IPv6 in Simulated or Real Environments**
    - References:
        - [How to configure IPv6 on Linux](https://www.computernetworkingnotes.com/linux-tutorials/how-to-configure-ipv6-on-linux.html)
        - [Mastering IPv6: A Complete Guide – Chapter 9](https://ipv6.net/guide/mastering-ipv6-a-complete-guide-chapter-9-build-your-first-ipv6-lab-from-zero-to-dual-stack-hero/)

- **Verifying and Testing IPv6 Configuration**
    - References:
        - [Configuring and Verifying IPv6 Addressing](https://www.torstechtalk.com/post/1-8-configuring-and-verifying-ipv6-addressing)
        - [How to manage IPv6 address validation](https://labex.io/tutorials/wireshark-how-to-manage-ipv6-address-validation-419398)

---

**Internal training available**
- **Visit Percipio for classes available through HPE on IPv6**
    - Percipio: [Percipio search](https://hpe.percipio.com/search?q=ipv6)
    - IPv6.net: [Mastering IPv6](https://ipv6.net/guide/mastering-ipv6-a-complete-guide-chapter-1-welcome-to-the-wild-world-of-ipv6/)

---

## Empty Student Progress Tracking Form

| Module                                 | Completed (Y/N) | Date Completed | Score/Notes                   |
|----------------------------------------|-----------------|----------------|-------------------------------|
| 1. Introduction to IPv6                |                 |                |                               |
| 2. IPv6 Addressing Architecture        |                 |                |                               |
| 3. IPv6 Address Types and Formats      |                 |                |                               |
| 4. IPv6 Routing                        |                 |                |                               |
| 5. Transition Mechanisms from IPv4     |                 |                |                               |
| 6. Security in IPv6                    |                 |                |                               |
| 7. Troubleshooting IPv6 Networks       |                 |                |                               |
| 8. IPv6 in Practice: Labs & Exercises  |                 |                |                               |

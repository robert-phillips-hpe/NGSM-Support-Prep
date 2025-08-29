# Preparing the Service Organization to Support Cray EX NGSM Systems

## Introduction

The Cray EX NGSM (Next-Generation System Management) platform represents a critical advancement in system management for high-performance computing (HPC) systems. It is imperative that the service organization is fully prepared to support NGSM systems in production environments. This document outlines the key preparations required to ensure we are equipped with the necessary tools, knowledge, and resources to provide seamless support for this product.  Because NGSM is not fully developed yet, this document should be considered a work in progress and will be updated as frequently as possible.  If anyone learns of new technologies, channels, confluence pages, etc.  Please edit this doc to add that information and keep us all informed.

## Importance of Preparation

Supporting the Cray EX NGSM system requires familiarity with the underlying technologies, processes, and 
software tools that form the backbone of the platform. The NGSM system incorporates modern, scalable, and 
efficient methodologies to manage Cray EX systems, which include advanced provisioning, configuration 
management, diagnostics, monitoring, and more.

The service organization must:
- Understand the software stack that powers NGSM systems.
- Have access to and actively participate in relevant communication channels.
- Be equipped with documentation, diagnostics tools, and technical expertise to resolve issues effectively.
- Collaborate with engineering teams to stay informed about updates and best practices.

---

## Key Slack Channels for NGSM Support

Slack serves as a vital platform for collaboration and communication among engineering, quality assurance, and 
service teams. The following Slack channels are focused on NGSM and should be actively monitored and reviewed by 
the service team:

1. **project_finch_apis**: Discussions and updates related to APIs used in NGSM systems.
2. **project-finch-boot-and-provisioning**: Conversations related to system boot processes and provisioning 
mechanisms.
3. **project-finch-configuration-management**: Configuration management topics, including tools and processes.
4. **project-finch-configuration-supergroup**: A broad channel covering overarching configuration-related 
efforts.
5. **project-finch-databases**: Database technologies and solutions used within NGSM systems.
6. **project-finch-diagnostics**: Diagnostics tools and processes for troubleshooting and support.
7. **project-finch-docs**: Documentation updates and resources for NGSM systems.
8. **project-finch-fsm-platform**: The Finite State Machine platform used within NGSM.
9. **project-finch-general**: General discussions and updates related to NGSM.
10. **project-finch-image-management**: Topics around managing images for deployment.
11. **project-finch-inventory-discovery-hw-mgmt**: Hardware inventory and discovery-related updates.
12. **project-finch-management-network**: Networking aspects of NGSM systems.
13. **project-finch-mgmt-nodes**: Management node operations and troubleshooting.
14. **project-finch-qe**: Quality engineering discussions related to NGSM.
15. **project-finch-service-monitoring**: Monitoring tools and processes for NGSM services.
16. **project-finch-ux**: User experience updates and considerations.

Active participation in these channels will ensure that the service organization remains informed and connected 
to the latest developments and issues.

---

## Required Software Products

The following software products are integral to the operation and support of NGSM systems. The service 
organization must gain proficiency in these technologies to provide effective support:

### Networking and Communication
1. **IPv6**: Modern networking protocol used for NGSM systems' communication.
2. **AnyCast**: A routing technique used to enhance network reliability and performance.
3. **DHCP**: Dynamic Host Configuration Protocol is a network protocol used to automate the process of assigning IP addresses and other network configuration parameters to devices 

### Storage Solutions
3. **Ceph**: Distributed storage solution used for managing data in NGSM systems.

### Load Balancing
4. **Haproxy**: High-performance load balancer to optimize service availability and reliability.

### Automation and Provisioning Tools
5. **Ansible**: Configuration management and automation tool used for provisioning and system setup.
6. **Cloud-init**: A service used for initial system configuration during boot-up.

### Collaboration and Development
7. **Gitea**: Lightweight, self-hosted Git service used for version control and collaboration.

---

## Self-Study Guides

Self-study is a key component of preparing the service organization to effectively support Cray EX NGSM systems. 
Comprehensive self-study guides will be developed to ensure the team has a deep understanding of the platform, 
its software stack, and operational workflows. These guides will include reference materials, exercises, and 
documentation to support independent learning.

### What to Expect in Self-Study Guides:
1. **Software Product Proficiency**: Guides will cover the listed software products (e.g., IPv6, Ceph, Ansible), 
focusing on their use within NGSM systems.
2. **Troubleshooting and Diagnostics**: Practical guidance on identifying, diagnosing, and resolving issues 
within NGSM environments.
3. **Workflow Familiarization**: Detailed walkthroughs of provisioning, configuration management, monitoring, 
and other NGSM processes.
4. **Collaborative Exercises**: Suggestions for team-based exercises to simulate real-world support scenarios.
5. **Documentation Review**: A focus on how to utilize and contribute to NGSM documentation effectively.

### Self Study Guides:
Guides will be added to this section as they become available for easy reference:



---

## Next Steps

To prepare the service organization to support Cray EX NGSM systems, the following steps should be taken:

1. **Self-Study**: Await detailed self-study guides and begin independent learning once resources are provided.
2. **Documentation Review**: Ensure all service team members review and become familiar with the latest 
documentation available in the `project-finch-docs` Slack channel.
3. **Slack Channel Monitoring**: Assign team members to monitor and participate in the relevant Slack channels 
for real-time updates and collaboration.
4. **Tool Setup**: Ensure all required tools (e.g., Ansible, Ceph, Haproxy) are installed, configured, and 
tested in a controlled environment.
5. **Knowledge Sharing**: Organize knowledge-sharing sessions to discuss best practices, troubleshooting 
techniques, and lessons learned from engineering and quality assurance teams.

---

## Conclusion

The success of Cray EX NGSM systems in production environments relies heavily on the readiness of the service 
organization to support this advanced platform. By actively participating in Slack channels, gaining proficiency 
in the required software products, and completing the self-study guides (to be provided later), the service 
organization will be well-positioned to provide effective support for this important product.


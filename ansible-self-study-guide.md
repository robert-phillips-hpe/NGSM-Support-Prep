# Ansible Self-Study Course

## Course Outline
1. Introduction to Ansible  
2. Setting Up Ansible  
3. Key Concepts in Ansible  
4. Inventory Files  
5. Modules and Ad-hoc Commands  
6. Writing Playbooks  
7. Roles and Ansible Galaxy  
8. Variables, Facts, and Templates  
9. Error Handling and Debugging  
10. Ansible Vault  
11. Using Ansible in Real-World Scenarios  
12. Final Project  

---

## Prerequisites, Knowledge, and Skills

To be successful in this course, learners should have the following prerequisites:

### 1. **Basic Linux Skills**
- Familiarity with Linux terminal commands, file structure, and common utilities like `ssh`, `scp`, and text editors (`vim` or `nano`).  
- **Source**:  
  - [Linux Command Line for Beginners](https://ubuntu.com/tutorials/command-line-for-beginners)  
  - [Introduction to Linux](https://www.edx.org/course/introduction-to-linux)  

### 2. **Understanding Networking Concepts**
- Basic knowledge of networking concepts, including IP addresses, DNS, and protocols like SSH.  
- **Source**:  
  - [Introduction to Internetworking](https://www.geeksforgeeks.org/computer-networks/introduction-of-internetworking/)  
  - [Linux Networking Tutorials](https://www.baeldung.com/linux/networking-series)  

### 3. **Python Basics**
- Ansible uses Python in its modules. Basic Python knowledge (variables, loops, and functions) will be helpful.  
- **Source**:  
  - [Learn Python](https://www.learnpython.org/)  
  - [Python for Beginners](https://www.python.org/about/gettingstarted/)  

### 4. **Familiarity with YAML**
- YAML knowledge is necessary as Ansible Playbooks are written in YAML format.  
- **Source**:  
  - [YAML Tutorial: A Complete Guide to Language, Format, and Syntax](https://www.cloudbees.com/blog/yaml-tutorial-everything-you-need-get-started)  
  - [YAML Syntax](https://yaml.org/spec/)  

### 5. **Don't forget The Linux Foundation**
- As HPE employees, we have access to The Linux Foundation.  Search [HPE Home](https://home.hpe.com) for "Linux Foundation"
- Can also go directly to [The Linux Foundation](https://www.linuxfoundation.org/)
---

## Module Details with Exercises and Resources

### Module 1: **Introduction to Ansible**
- **Time Frame**: 1 hour  
- **Topics**:  
  - What is Ansible?  
  - Configuration Management Overview.  
  - How Ansible Works: Agentless Architecture.  
  - Use cases for Ansible.  
- **Exercise**:  
  - Research one real-world use case for Ansible and write a one-page summary.  
- **Test Questions**:  
  - What does "agentless" mean in the context of Ansible?  
  - What are three common use cases for Ansible?  
- **Resources**:  
  - [Geeksforgeeks Ansible](https://www.geeksforgeeks.org/linux-unix/ansible/)  
  - [Introduction to Configuration Management](https://www.redhat.com/en/topics/automation/what-is-configuration-management)  

---

### Module 2: **Setting Up Ansible**
- **Time Frame**: 2 hours  
- **Topics**:  
  - Installing Ansible on Linux.  
  - Setting up a Control Node and Managed Nodes.  
  - Testing connectivity between nodes.  
- **Exercise**:  
  - Install Ansible on your machine. Set up SSH keys for two managed nodes and ping them using `ansible all -m ping`.  
- **Test Questions**:  
  - What command is used to test connectivity between nodes?  
  - How do you set up SSH keys for managed nodes?  
- **Resources**:  
  - [Installing Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)  
  - [Setting Up SSH Keys](https://www.ssh.com/academy/ssh/keygen)  

---

### Module 3: **Key Concepts in Ansible**
- **Time Frame**: 1 hour  
- **Topics**:  
  - Control Node and Managed Node.  
  - Inventory Files.  
  - Modules.  
  - Playbooks and Tasks.  
- **Exercise**:  
  - Write a summary explaining the relationship between Playbooks, Tasks, and Modules.  
- **Test Questions**:  
  - What is the difference between a Control Node and a Managed Node?  
  - What role do Modules play in Ansible?  
- **Resources**:  
  - [Ansible Glossary](https://docs.ansible.com/ansible/latest/reference_appendices/glossary.html)  

---

### Module 4: **Inventory Files**
- **Time Frame**: 2 hours  
- **Topics**:  
  - Syntax of Inventory Files.  
  - Defining Groups and Host Variables.  
  - Dynamic Inventory.  
- **Exercise**:  
  - Create a static inventory file with at least two groups and three hosts.  
  - Create a sample dynamic inventory script.  
- **Test Questions**:  
  - What is the difference between static and dynamic inventory?  
  - How are groups defined in inventory files?  
- **Resources**:  
  - [Ansible Inventory](https://docs.ansible.com/ansible/latest/inventory_guide/intro_inventory.html)
  - [The Beginner's Guide to the Ansible Inventory](https://www.packetcoders.io/the-beginners-guide-to-the-ansible-inventory/)  

---

### Module 5: **Modules and Ad-hoc Commands**
- **Time Frame**: 3 hours  
- **Topics**:  
  - Understanding Ansible Modules.  
  - Using Ad-hoc Commands.  
- **Exercise**:  
  - Use the `ansible.builtin.file` module to create a file on a managed node.  
  - Use the `ansible.builtin.package` module to install a package.  
- **Test Questions**:  
  - What are Ad-hoc commands used for?  
  - How would you create a file using the `file` module?  
- **Resources**:  
  - [Ansible Modules](https://docs.ansible.com/ansible/latest/modules/modules_by_category.html)
  - [Ansible Module](https://www.geeksforgeeks.org/devops/ansible-module/)  

---

### Module 6: **Writing Playbooks**
- **Time Frame**: 3 hours  
- **Topics**:  
  - YAML Basics.  
  - Structure of a Playbook.  
  - Writing Multi-task Playbooks.  
- **Exercise**:  
  - Write a playbook to install and start a web server on a managed node.  
- **Test Questions**:  
  - What are the key components of a Playbook?  
  - How do you define tasks in a Playbook?  
- **Resources**:  
  - [Ansible Playbook Basics](https://docs.ansible.com/ansible/latest/user_guide/playbooks.html)
  - [Ansible Playbook](https://www.geeksforgeeks.org/devops/what-is-an-ansible-playbook/)

---

### Module 7: **Roles and Ansible Galaxy**
- **Time Frame**: 2 hours  
- **Topics**:  
  - Creating Roles.  
  - Using Roles in Playbooks.  
  - Using Ansible Galaxy.  
- **Exercise**:  
  - Create a role for installing and configuring a database server.  
- **Test Questions**:  
  - What is the purpose of roles in Ansible?  
  - How do you import roles from Ansible Galaxy?  
- **Resources**:  
  - [Ansible Roles](https://docs.ansible.com/ansible/latest/user_guide/playbooks_reuse_roles.html)  
  - [Ansible Roles]([https://galaxy.ansible.com/](https://www.geeksforgeeks.org/devops/ansible-roles/))  

---

### Module 8: **Variables, Facts, and Templates**
- **Time Frame**: 2 hours  
- **Topics**:  
  - Defining Variables.  
  - Using Facts.  
  - Jinja2 Templates.  
- **Exercise**:  
  - Write a playbook that uses a Jinja2 template to configure a web server.  
- **Test Questions**:  
  - What are Ansible Facts used for?  
  - How do you define Variables in Playbooks?  
- **Resources**:  
  - [Ansible Variables and Facts](https://docs.ansible.com/ansible/latest/user_guide/playbooks_variables.html)  
  - [Jinja2 Templates](https://jinja.palletsprojects.com/en/3.1.x/templates/)  

---

### Module 9: **Error Handling and Debugging**
- **Time Frame**: 1 hour  
- **Topics**:  
  - Handling Failed Tasks.  
  - Debugging Playbooks.  
- **Exercise**:  
  - Write a playbook with intentional errors and debug them using the `debug` module.  
- **Test Questions**:  
  - How can you debug Playbooks effectively?  
- **Resources**:  
  - [Ansible Debugging Tasks](https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_debugger.html)
  - [Debugging Ansible Workflows: A Comprehensive Guide](https://betterstack.com/community/guides/linux/debug-ansible-workflows/)

---

### Module 10: **Ansible Vault**
- **Time Frame**: 1 hour  
- **Topics**:  
  - Securing Sensitive Data with Vault.  
  - Using Vault in Playbooks.  
- **Exercise**:  
  - Encrypt sensitive variables using Vault and use them in a playbook.  
- **Test Questions**:  
  - How do you encrypt data using Ansible Vault?  
- **Resources**:  
  - [Ansible Vault](https://docs.ansible.com/ansible/latest/user_guide/vault.html)
  - [How to Use Ansible Vault in Playbook? Secure Your Configuration](https://www.cherryservers.com/blog/ansible-vault-in-playbook)

---

### Module 11: **Using Ansible in Real-World Scenarios**
- **Time Frame**: 2 hours  
- **Topics**:  
  - Automating Server Setup.  
  - Deploying Applications.  
- **Exercise**:  
  - Write a playbook to deploy a complete application stack (web server and database).  
- **Resources**:  
  - [20 Real-World Ansible Scenarios with Practical Answers](https://dev.to/latchudevops/20-real-world-ansible-scenarios-with-practical-answers-2959)
  - [Ansible Use Cases: Real-World Examples of Ansible in Action](https://learnansible.dev/article/Ansible_Use_Cases_RealWorld_Examples_of_Ansible_in_Action.html)

---

### Module 12: **Final Project**
- **Time Frame**: 4 hours  
- **Topics**:  
  - Combine all learned concepts to automate a multi-node setup.  
- **Exercise**:  
  - Create a project that sets up a web application with a database across multiple nodes.  
- **Test Questions**:  
  - What was the most challenging aspect of the project, and how did you resolve it?  

---

## Total Time Frame
- **Estimated Completion Time**: 24 hours  

---

## List of URL's Used in This Document

1. [Linux Command Line for Beginners](https://ubuntu.com/tutorials/command-line-for-beginners)  
2. [Introduction to Linux](https://www.edx.org/course/introduction-to-linux)  
3. [Introduction to Internetworking](https://www.geeksforgeeks.org/computer-networks/introduction-of-internetworkin  
4. [Linux Networking Tutorials](https://www.baeldung.com/linux/networking-series)  
5. [Learn Python](https://www.learnpython.org/)  
6. [Python for Beginners](https://www.python.org/about/gettingstarted/)  
7. [YAML Tutorial: A Complete Guide to Language, Format, and Syntax](https://www.cloudbees.com/blog/yaml-tutorial-everything-you-need-get-started)  
8. [YAML Syntax](https://yaml.org/spec/)  
9. [Geeksforgeeks Ansible](https://www.geeksforgeeks.org/linux-unix/ansible/)  
10. [Introduction to Configuration Management](https://www.redhat.com/en/topics/automation/what-is-configuration-management)  
11. [Installing Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)  
12. [Setting Up SSH Keys](https://www.ssh.com/academy/ssh/keygen)  
13. [Ansible Glossary](https://docs.ansible.com/ansible/latest/reference_appendices/glossary.html)  
14. [Ansible Inventory](https://docs.ansible.com/ansible/latest/inventory_guide/intro_inventory.html)
15. [The Beginner's Guide to the Ansible Inventory](https://www.packetcoders.io/the-beginners-guide-to-the-ansible-inventory/)  
16. [Ansible Modules](https://docs.ansible.com/ansible/latest/modules/modules_by_category.html)
17. [Ansible Module](https://www.geeksforgeeks.org/devops/ansible-module/)   
18. [Ansible Playbook Basics](https://docs.ansible.com/ansible/latest/user_guide/playbooks.html)
19. [Ansible Playbook](https://www.geeksforgeeks.org/devops/what-is-an-ansible-playbook/) 
20. [Ansible Roles](https://docs.ansible.com/ansible/latest/user_guide/playbooks_reuse_roles.html)  
21. [Ansible Roles]([https://galaxy.ansible.com/](https://www.geeksforgeeks.org/devops/ansible-roles/))  
22. [Ansible Variables and Facts](https://docs.ansible.com/ansible/latest/user_guide/playbooks_variables.html)  
23. [Jinja2 Templates](https://jinja.palletsprojects.com/en/3.1.x/templates/)  
24. [Ansible Debugging](https://docs.ansible.com/ansible/latest/user_guide/debugging.html)
25. [Debugging Ansible Workflows: A Comprehensive Guide](https://betterstack.com/community/guides/linux/debug-ansible-workflows/)
26. [Ansible Vault](https://docs.ansible.com/ansible/latest/user_guide/vault.html)
27. [How to Use Ansible Vault in Playbook? Secure Your Configuration](https://www.cherryservers.com/blog/ansible-vault-in-playbook)
28. [20 Real-World Ansible Scenarios with Practical Answers](https://dev.to/latchudevops/20-real-world-ansible-scenarios-with-practical-answers-2959)
29. [Ansible Use Cases: Real-World Examples of Ansible in Action](https://learnansible.dev/article/Ansible_Use_Cases_RealWorld_Examples_of_Ansible_in_Action.html) 

# AnsibleDemos
This repository has some of the playbooks which can help you get familiarized with Ansible! Do feel free to add your own experiments with playbooks if they can help others solve issues and learn! Happy coding :D


This playbook aims at installation of Tomcat 8 using Ansible. The installation steps have been achieved using Ansible modules as much as possible. The idea is to get familiarized with how 
Ansible works and how to write playbooks.


Do raise PRs if you feel the code can be improved (I'm pretty sure it can :P). It'll be fun to see where it goes! :D

Will be adding more generic codes for installations / setups. Please feel free to suggest some infrastructure setups you would like to see. Hoping to get a great learning curve out of this experience! :D :D


The playbook was written in a system with the below mentioned specs

OS: RHEL 7.5
Ansible Version: 2.5
Tomcat 8
Java 1.8+

Add the necessary values in the hosts file as per your need.
The username and password for the Tomcat manager can be changed in the variables section of the tomcat role. Default tomcat/tomcat.

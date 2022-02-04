# Ansible_Cisco_P2P_Migration
This repo is created to share complete ansible script with each step tested to migrate Point to Point links between Cisco Devices

This project was to migrate Point to Point Links on Cisco Devices using Ansible

Ansible Playbook is written to implement changes on 1 device at a time. However due to parallel execution, changes are simultaneously implemented on all paritcipating deviecs. 

Post-check will be performed to ensure OSPF Neighbor is FULL/ Established else change is backed out to Old config

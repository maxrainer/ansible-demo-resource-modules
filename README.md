# **Ansible Resource Modules Demo**

### **Overview**
Some Ansible playbooks to demonstrate different networking use cases with resource modules. 

### **Examples**
* device pull<br/>
    read configuration from device and push data to GitHub SoT
* device push<br />
    push configs to device, test operational state and rollback
* create VLAN<br />
    Cisco Nexus only: check if VLAN is consistent and create VLAN 

### **Usage**
Matching inventory can be found here: 
[Demo SoT](https://github.com/maxrainer/net-demo-data)

* ansible-playbook -i ../../inventory/net-demo-data/virl1.yaml.yml device_pull.yml

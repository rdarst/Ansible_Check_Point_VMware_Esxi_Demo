# Demo using the new Ansible module for Check Point added in Ansible 2.9

**Install the development branch of Ansible 2.9 that includes the new Check Point module**

**This demo is dependant on a Check Point gateway setup as a template in ESXi**
```
The gateway should have a username/password set
The gateway should be setup with eth0 set to aquire a DHCP address on startup
The gateway should be setup with bash for the shell for the admin user
```

**This demo is dependant on another VM that is setup to aquire a DHCP address on startup**
```
In this setup an Ubuntu instance is used from a template that is setup for DHCP
```

Adjust the playbooks to your setup for Virtual Networks, vCenter and Storage locations

Run the demo using the create script

Delete the demo using the delete script



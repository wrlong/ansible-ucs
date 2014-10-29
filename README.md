ansible-ucs
===============

An ansible playbook and associated modules for UCS configuration, using the UCS Python SDK for UCSM API integration.

It modularizes key functions for the UCS Python SDK, supporting coordinated configuration of UCS elements and service profile templates. 
 
### Dependencies

Download and install the UCS Python SDK:

https://communities.cisco.com/docs/DOC-37174

### Sample files
Sample UCS Service Profile template playbook using roles and inclusions
- openstack-build-sample.yml

### Usage
#### To run a playbook:
```bash
$ ansible-playbook -i hosts openstack-build-sample.yml
```
#### To run an ad hoc command using a module:
```bash
$ ansible -m <module_name> <params>
```

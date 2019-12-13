# Ansible Scripts Use To Test The AWX Project

AWX Project is the upstream project for Ansible Tower, a commercial Red Hat product that provide web-based user interface, REST API, and task engine built on top of Ansible.

The Ansible scripts are created at it simplest form purposedly to test AWX workflow feature and allow for modular design and reusable script. 

2019-12-12 Update
reboot-if-required.yaml
- using stat module to check /var/run/reboot-required file exist on Ubuntu
- update to use the reboot module replacing the command module to reboot
- add reboot check for CentOS

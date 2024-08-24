# App-Servers-using-Ansible
Ansible automates and ensures consistent configuration and management of application servers using an agentless approach.

a. Create an inventory file /home/thor/ansible/inventory on jump_host and add all application servers as managed nodes.


b. Create a playbook /home/thor/ansible/playbook.yml on the jump host to copy the /usr/src/finance/index.html file to all application servers, placing it at /opt/finance.


Note: Validation will run the playbook using the command ansible-playbook -i inventory playbook.yml. Ensure the playbook functions properly without any extra arguments

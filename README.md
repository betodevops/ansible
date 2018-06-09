# ansible

**Pre-req**

Install Ansible
Install aws cli
Vpc configured

**Setup:**

Change environments variables in ec2-vars/webservers.yml file 

ansible-playbook -vv -i /etc/ansible/hosts, -e "type=webservers" provide_ec2.yml  -vvvvvv
# ansible
# ansible

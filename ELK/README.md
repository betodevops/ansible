First of all you need to download Ec2 modules from https://aws.amazon.com/pt/blogs/apn/getting-started-with-ansible-and-dynamic-amazon-ec2-inventory-management/

ansible-playbook -i inventory/staging/ec2.py elk.yml -u ubuntu -vvvvv


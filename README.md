Install Wordpress on Centos 7 using Ansible Role. Here three different role:
- web_server
- mariadb_server
- wordpress

Please change the database name, user and password from group_vars/server_group_1 and rename the group_vars/server_group_1 to your host group name accordingly. 

Run the below command to install Wordpress with Apache, PHP and MariaDB

# ansible-playbook playbook.yml -i inventory.txt

Here inventory.txt is your inventory file. 

# Ansible_simple_playbook
it is a simple playbook to install nginx on a server and deploy a simple html file on it
# command to start ansible playbook 
ansible-playbook -i hosts /home/ansible/install_nginx_and_publish_html.yml
# command to check hosts
ansible-inventory -i /home/ansible/hosts --list;
# sample success output 
![image](https://github.com/ehsanDadashi/Ansible_simple_playbook/assets/29996315/8819edb4-fd92-4976-9815-335295798d42)

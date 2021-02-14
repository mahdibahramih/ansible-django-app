# django_rolebase_ansible
its a ansible-playbooks rolebase file that deploy your python-django app easily
for usage you must set some var(like domain,app git repo,...) in vars.yml file 
# Getting start
## Install ansible
 sudo apt update
 sudo apt install software-properties-common
 sudo apt-add-repository --yes --update ppa:ansible/ansible
 sudo apt install ansible

 ## Run playbook
 Notify that You must modify variables in vars.yml file
 ansible-playbook site.yml -i hosts.yml
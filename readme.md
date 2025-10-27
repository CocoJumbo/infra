Ansible script for install assets to bare metal, on clean Ubuntu 24.04.3 LTS

To apply playbook
1. Make sure Ansible is installed 

ansible --version

If not installed:

sudo apt update
sudo apt install ansible -y

2. Go to repo

ansible-playbook -i inventory.ini playbooks/single_node_k8s.yml
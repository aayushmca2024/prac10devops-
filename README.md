use the command 

sudo apt update
sudo install ansible
sudo install python3

ansible-playbook -i inventory/inventory.ini playbooks/testplaybook.yml --ask-become-pass
use the pass that you have for sudo
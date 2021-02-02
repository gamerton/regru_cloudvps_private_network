# regru_cloudvps_private_network

Ansible playbook to set up private network on [REG.RU CloudVPS](https://www.reg.ru/vps/cloud/?rlink=reflink-6314721)

git clone https://github.com/gamerton/regru_cloudvps_private_network.git


cd regru_cloudvps_private_network
ansible-galaxy install mrlesmithjr.netplan

edit inventory file

ansible-playbook -i inventory.ini network.yml


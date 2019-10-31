# Magento Deployment

All configuration for the properties for the magento installation live at group_vars/all.yml

In there please configure the properties specified

# Usage

The following command will execute the installation

ansible-playbook --private-key=.private-key.pem -i hosts.yml  magento.yml --become

The private key is the ssh key to ssh to the vms
the hosts.yml should contain all hosts you wish to target


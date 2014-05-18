ansible_vagrant_config_tools
==========

Description
------------
Early version of a playbook that writes an inventory and a Vagrantfile based on
the production inventory. This enables bringing up a development duplicate of
any host in the production inventory with Vagrant.

Example usage
-------------
ansible-playbook -i production -D generate_inventory_and_hosts.yml
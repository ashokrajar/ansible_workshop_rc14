RootConf 2014 - Ansible with Puppet at Scale
============================================

[RootConf 2014 - Ansible with Puppet at Scale](https://funnel.hasgeek.com/rootconf2014/1121-ansible-with-puppet-at-scale)

There are 2 Vagrantfiles currently.

1st one is a simple demo of how to use vagrant with ansible. Copy Vagrantfile_sudoers to Vagrantfile

2nd one has 3 machines in them so you need to make sure you first bring up all machines and then run provision. Copy Vagrantfile_webservers to Vagrantfile

1. vagrant up --no-provision ( No ansible will be run as a result of this command )
2. vagrant provision ( Now ansible kicks in ) .

Make sure the Vagrantfile is one folder above the ansible folder

ls  -lh
total 40
-rw-r--r--   1 Madhurranjan  Group 675B May 14 23:24 Vagrantfile
drwxr-xr-x  20 Madhurranjan  Group 680B May 14 23:28 ansible_workshop_rc14
-rw-r--r--   1 Madhurranjan  Group 81B May 14 21:15 vagrant_ansible_inventory_default
-rw-r--r--   1 Madhurranjan  Group 82B May 14 22:41 vagrant_ansible_inventory_machine1
-rw-r--r--   1 Madhurranjan  Group 82B May 14 22:41 vagrant_ansible_inventory_machine2
-rw-r--r--   1 Madhurranjan  Group 82B May 14 22:42 vagrant_ansible_inventory_machine3

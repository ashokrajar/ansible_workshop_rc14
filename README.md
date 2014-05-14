RootConf 2014 - Ansible with Puppet at Scale
============================================

[RootConf 2014 - Ansible with Puppet at Scale](https://funnel.hasgeek.com/rootconf2014/1121-ansible-with-puppet-at-scale)

There are 2 Vagrantfiles currently.

1st one is a simple demo of how to use vagrant with ansible. Copy Vagrantfile_sudoers to Vagrantfile

2nd one has 3 machines in them so you need to make sure you first bring up all machines and then run provision. Copy Vagrantfile_webservers to Vagrantfile

1. vagrant up --no-provision ( No ansible will be run as a result of this command )
2. vagrant provision ( Now ansible kicks in ) .

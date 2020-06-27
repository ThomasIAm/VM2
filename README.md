# VM2

This is an Ansible implementation for simple a cloud portal. This was a school project for the VM2 class.

# Features!

  - A playbook per customer.
  - Using Ansible roles.
  - Using Ansible vault for passwords, etc.
  - Using Vagrant to deploy VMs.
  - The Ansible inventory and Vagrant hosts file are in YAML for easy manipulation in PHP.
  - Public/private keys per customer for secure operations.
  - Playbooks for databaseservers, webservers, and loadbalancers.
  - Almost everything is configurable using variables.

### Tech

The repository uses a number of open source projects to work properly:

* [Ansible] - The simplest way to automate apps and IT infrastructure. Application Deployment + Configuration Management + Continuous Delivery.
* [Vagrant] - Enables users to create and configure lightweight, reproducible, and portable development environments.

### Installation

The VM2 portal requires [Ansible] v2.9 and [Vagrant] v2.2 to run.

Install the dependencies, run `vagrant up`, and `ansible-playbook playbook.yml --vault-id @ansible_vault_pass`.


[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [Ansible]: <https://www.ansible.com/>
   [Vagrant]: <https://www.vagrantup.com/>

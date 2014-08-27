Ansible VM
==========

- Ubuntu 14.04 Trusty 64bit
- NGINX + PHP5-FPM
- PHP 5.5
- NodeJS v0.10.29
- Automatic NGINX Site Configuration
- Automatic Database Configuration

# Usage

1. Bring this repo into your project as the ansible/ folder in the root. You could just copy it there or add it as a submodule: `git submodule add git@github.com:heybigname/ansible.git`
2. Copy the Vagrantfile into your application root
3. Modify your Vagrantfile
    - set the name for the box (the part that says CHANGE ME)
    - configure your hostname, database details, site details, etc
4. Install Vagrant, VirtualBox, and Ansible.
5. Just run `vagrant up`

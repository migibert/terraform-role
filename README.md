Terraform
========

Ansible role to install Terraform on Linux machines.
Install it with `ansible-galaxy install migibert.terraform`

Role Variables
--------------

Here are the role variables and their default values.
terraform_version: 0.3.6
terraform_dir: /opt/terraform

Example Playbook
-------------------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - role: migibert.terraform

License
-------

MIT

Author Information
------------------

Mikael Gibert, Developer / DevOps.

Terraform
========
[![Galaxy](http://img.shields.io/badge/ansible--galaxy-terraform-blue.svg)](https://galaxy.ansible.com/list#/roles/2831)
[![License](http://img.shields.io/:license-mit-blue.svg)](http://doge.mit-license.org)  
[![Circle CI](https://circleci.com/gh/migibert/terraform-role/tree/master.svg?style=shield)](https://circleci.com/gh/migibert/terraform-role)

Ansible role to install Terraform on Linux machines.

Install it with `ansible-galaxy install migibert.terraform`

Role Variables
--------------

Here are the role variables and their default values. Default password for user terraform is terraform.
```
terraform_version: 0.6.11
terraform_dir: /opt/terraform
terraform_user: terraform
terraform_user_password: $6$uoCgixKJL4cFyIT$U7FisaA6GAdosBpGde.4NS00vaAg4tGmR63eBQQMsd8LiHUjetq6HDXG10719JwbNmQUSLzvG6zq8DOVOggIw1
```

Example Playbook
-------------------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
- hosts: all
  roles:
    - role: migibert.terraform
```

License
-------

MIT

Author Information
------------------

Mikael Gibert, Developer / DevOps.

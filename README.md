terragrunt
==========

[![Build Status](https://travis-ci.org/andrelohmann/ansible-role-terragrunt.svg?branch=master)](https://travis-ci.org/andrelohmann/ansible-role-terragrunt)

Use this role to install terragrunt.

Requirements
------------

This role requires ubuntu.

Role Variables
--------------

    terragrunt_version: 0.14.7 #defaults to 'latest'

Example Playbook
----------------

    - hosts: terragrunt
      roles:
         - andrelohmann.terragrunt

License
-------

MIT

Author Information
------------------

https://github.com/andrelohmann

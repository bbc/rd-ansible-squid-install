rd-ansible-squid-install
=========

This module installs a basic caching squid proxy. By default it allows all traffic on any local addresses and listens on 8080.

Requirements
------------

This module requires Ansible 2.6

Role Variables
--------------

See defaults for variables and descriptions

Example Playbook
----------------

Example to call:

    - hosts: all
      roles:
         - { role: rd-ansible-squid-install }

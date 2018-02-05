Role Name
=========

Ansible role for installing Prometheus Node Exporter. 

Requirements
------------

n/a

Role Variables
--------------

todo

Dependencies
------------

Following Ansible roles are required:

    - ansible-role-firewalld-prometheus-node-exporter

Example Playbook
----------------

How to use the role:

    - hosts: all
      roles:
         - { role: firewalld-prometheus-node-exporter }
         - { role: prometheus-node-exporter }


Author Information
------------------

[Jakub Jarosz](https://twitter.com/qba73)


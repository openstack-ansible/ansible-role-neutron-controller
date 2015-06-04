neutron-controller ansible role
===============================

[![Build Status](https://travis-ci.org/marklee77/ansible-role-neutron-controller.svg?branch=master)](https://travis-ci.org/marklee77/ansible-role-neutron-controller)

The purpose of this role is to deploy neutron-controller onto Ubuntu. 

Role Variables
--------------

- openstack_mysql_host: 127.0.0.1
- openstack_mysql_port: 3306
- openstack_rabbitmq_host: 127.0.0.1
- openstack_rabbitmq_port: 5672
- openstack_log_verbose: true
- openstack_log_debug: false
- openstack_identity_region: RegionOne

Example Playbook
-------------------------

    - hosts: all
      sudo: True
      roles:
        - neutron-controller

License
-------

GPLv2

Author Information
------------------

http://stillwell.me

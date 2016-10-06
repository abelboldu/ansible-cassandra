Role Name
=========

Ansible role to install cassandra cluster for MidoNet 

Role Variables
--------------

`cassandra` dictionary or group in hosts inventory. See example:

    [cassandra]
    cs1.midoexample.net
    cs2.midoexample.net
    cs3.midoexample.net

Example Playbook
----------------

    hosts: cassandra
      roles:
        - role: ansible-cassandra
          cassandra_hosts: '{{ groups["cassandra"] }}'

License
-------

Apache 2.0

Author Information
------------------

Abel Boldú < abel.boldu@gmx.com >

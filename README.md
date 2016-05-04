troykinsella.openstack-client
=============================

An ansible role to install OpenStack clients: ceilometer, cinder, glance, heat, keystone, neutron, nova, swift, and trove.

Dependencies
------------

* troykinsella.python

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: troykinsella.openstack-client

License
-------

MIT

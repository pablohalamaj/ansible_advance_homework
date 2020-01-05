Role Name
=========

This role delete all the instances on default's OpenStack Tenant.

Requirements
------------

The host running this playbook needs to have configured the openstack API parameters and the openstacksdk.
OpenStackClient looks for clouds.yaml file in:

* Current working directory
* ~/.config/openstack
* /etc/openstack

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: osp-instance-delete }

License
-------

BSD

Author Information
------------------

pablo.halamaj(at)sendati.com

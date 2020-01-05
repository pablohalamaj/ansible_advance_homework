Role Name
=========

This role setups networks, SSH keys, security_groups for instances on default's OpenStack Tenant.

Requirements
------------

The host running this playbook needs to have configured the openstack API parameters and the openstacksdk.
OpenStackClient looks for clouds.yaml file in:

* Current working directory
* ~/.config/openstack
* /etc/openstack

Role Variables
--------------

* osp_networks: a list of networks and they parameters

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: osp-setup }

License
-------

BSD

Author Information
------------------

pablo.halamaj(at)sendati.com

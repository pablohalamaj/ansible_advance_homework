Role Name
=========

This role create instances on the default's Openstack Tennant.

Requirements
------------

The host running this playbook needs to have configured the openstack API parameters and the openstacksdk.
OpenStackClient looks for clouds.yaml file in:

* Current working directory
* ~/.config/openstack
* /etc/openstack


Role Variables
--------------

* osp_startup_timeout: the timeout in seconds to wait for the SSH connection to the instances to success
* osp_servers: a list of instances and their parameteres, for a complete list see vars.main.yml


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: osp-servers }

License
-------

BSD

Author Information
------------------

pablo.halamaj(at)sendati.com

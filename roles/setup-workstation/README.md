Role Name
=========

Install and configure all the necesary tools for a Standalone instances of Ansibles Tower with connection to a RHOSP farm.

Role Variables
--------------

* osp_networks: list of networks for openstack and they configuration parameters.
* OSP_GUID: ID of the OPENTLC project with the OPENSTACK instances.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: setup-workstation }

License
-------

BSD

Author Information
------------------

pablo.halamaj(at)sendati.com

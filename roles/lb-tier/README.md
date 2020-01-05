Role Name
=========

This role Install HAPROXY and the necesary files on the loadbalancing instances.

Requirements
------------

A Red Hat kind of Operating System (RHEL, CentOS, Fedora, etc).

Role Variables
--------------

* apps or tag_AnsibleGroup_apps: A group with the inventory of the Application Servers to create the LoadBalancing Farm

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: lb-tier }

License
-------

BSD

Author Information
------------------

Email: pablo.halamaj(at)sendati.com

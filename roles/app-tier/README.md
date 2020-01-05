Role Name
=========

This role Install Tomcat and the necesary files on the APP instances.

Requirements
------------

A Red Hat kind of Operating System (RHEL, CentOS, Fedora, etc).

Role Variables
--------------

* app-tier-root: Default directory for WEBAPPS root of tomcat (defaults to /usr/share/tomcat/webapps ).

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: app-tier }

License
-------

BSD

Author Information
------------------

Email: pablo.halamaj(at)sendati.com

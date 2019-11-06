Role Name
=========

This role will install the application software.

Requirements
------------
Requires the general-config role to enable the software repos

Role Variables
--------------

App server: Tomcat
Port 8080
WebRoot: /usr/share/tomcat/webapps/ROOT



Example Playbook
----------------
To include the role as follow

  roles:
    - general-config
    - app-tier
  tags:
    - app


License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).

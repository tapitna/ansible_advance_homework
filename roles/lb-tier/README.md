Role Name
=========

This role will install and configure HAproxy

Requirements
------------

Include the general-config role to configure the software repos
The default config can be locate in templates/haproxy.cfg.j2

Role Variables
--------------
define the proxy port
haproxy_port: 80

Example Playbook
----------------
To include the role use this code:

  roles:
    - general-config
    - lb-tier
  tags:
    - lb

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).

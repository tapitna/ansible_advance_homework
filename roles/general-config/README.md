Role Name
=========

This is the general config role for all the 3 Tier app servers
Will configure sudo and sofware repos.

Requirements
------------

The repository config file should be locate in templates/open_3-tier-app.repo.j2

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------
This role should be include before other roles
  roles:
    - general-config

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).

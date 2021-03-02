Role Name
=========

This role install postgresql in `appdbs` group servers.

Requirements
------------

* The Servers that use this role must be RHEL kind (RHEL, CentOS, Fedora, etc)

  
Role Variables
--------------

* `own_repo_path`: hostname of the cdm that contain the repo (package rpm)


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: db-tier }

License
-------

BSD

Author Information
------------------

Gonzalo Acosta <gonzalo.acosta@semperti.com>

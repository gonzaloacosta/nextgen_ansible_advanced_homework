Role Name
=========

This role install common repository package for all servers in three tier solution.

Requirements
------------

* The Servers that use this role must be RHEL kind (RHEL, CentOS, Fedora, etc)
* When use the playbook must be pass `--ask-vault-pass` with the correct pass or add the credentials in ansible tower to decrytp the vault variable.
  
Role Variables
--------------

* `own_repo_path`: hostname of the cdm that contain the repo (package rpm)


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: base-config }

License
-------

BSD

Author Information
------------------

Gonzalo Acosta <gonzalo.acosta@semperti.com>

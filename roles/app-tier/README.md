Role Name
=========

This role install web server Tomcat and all the necesary in `apps` groups in any cloud.

Requirements
------------

* The Servers that use this role must be RHEL kind (RHEL, CentOS, Fedora, etc)

Role Variables
--------------

* `payload`: name of web server, in this case `tomcat`
* `tomcat_web_root`:  directory root path of tomcat `/usr/share/tomcat/webapps/ROOT`


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

Gonzalo Acosta <gonzalo.acosta@semperti.com>

Role Name
=========

This role install load balancer `payload` in frontend servers.

Requirements
------------

* The Servers that use this role must be RHEL kind (RHEL, CentOS, Fedora, etc)

  
Role Variables
--------------

* `payload`: name of load balancer service (default `haproxy`)


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

Gonzalo Acosta <gonzalo.acosta@semperti.com>

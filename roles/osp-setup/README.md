Role Name
=========

The role provision all resource in Openstack for deploy instance server.

Requirements
------------

The host running this role need to have configured openstacksdk and openstack API parameters.

* Directories
  - `/etc/openstack/`
  - `$HOME/.config/openstack`

* Var Env
- `export OS_CLOUD=<cloud name>`

Role Variables
--------------

* osp_servers: a list of all the install that you need deploy on top Openstack
 
Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: osp-setup }

License
-------

BSD

Author Information
------------------

gonzalo.acosta@semperti.com

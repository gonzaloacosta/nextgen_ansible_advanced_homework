Role Name
=========

Bring openstack info and add groups in-memory inventory.

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

* `osp_cloud`: openstack
* `osp_region`: regionOne

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: osp-facts }

License
-------

BSD

Author Information
------------------

gonzalo.acosta@semperti.com

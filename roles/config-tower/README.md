Role Name
=========

Role for configuration project, inventories, jobs and workflows at Ansible Tower

Requirements
------------

The host where the role will be executed must be have tower_cli.

Role Variables
--------------

There are a lot of variable in this role but the relevant that must be defined are:

* tower_host: URL for Ansible Tower host.
* tower_GUI: ID of the Homework lab at OpenTLC.
* github_repo: GitHub repo that include all the playbooks (student fork).
* password: Tower admin password protected with ansible vault in credentials.yml 
* os_GUID: ID of the Openstack lab in OpenTLC.
* osp_DOMAIN: Domain of the Openstack lab in OpenTLC. 
* host_name: Jump server and extension of Ansible Tower in Openstack lab
* opentlc_password: OpenTLC student password.
* path_to_opentlc_key: OpenTLC student SSH key
* EMAIL: Student email.
* REGION_NAME: AWS Region name for deploy the lab in OpenTLC.


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: config-tower }

License
-------

BSD

Author Information
------------------

gonzalo.acosta@semperti.com

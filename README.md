Role Name
=========

Role to setup NTP vars and get time running

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

Role vars in use are below. These will be added to Foreman for use with automation.

"primary_ntp_pool"
"secondary_ntp_pool"

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

Testing Role
------------

You can test this role easily. Git the role and change to test directory.

Run : ansible-playbook -i inventory main.yml

License
-------

BSD

Author Information
------------------

Made by Sean Helmus
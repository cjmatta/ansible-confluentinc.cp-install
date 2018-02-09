confluentinc.cp-install
=========

Download and install Confluent Platform Enterprise

Role Variables
--------------

|Role|Description|
|---|---|
|confluent_user| the username of the principal that will run kafka|
|confluent_group| the group name of the principal that will run kafka|
|cp_version| the Confluent Platform version to install|

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: cp-install, cp_version: 4.0.0, confluent_user: kadmin, confluent_group: kadmin }

License
-------

BSD

Author Information
------------------
Chris Matta - chris@confluent.io
https://confluent.io
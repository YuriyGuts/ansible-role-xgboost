yuriyguts.xgboost
=================

An Ansible role to install XGBoost on Linux.

Requirements
------------

* `pip` on the target system.

* If the target environment requires running `pip` with elevated privileges,
  make sure to set `xgboost_python_package_manager_become: yes` in your playbook.

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml).

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: modeling
      roles:
         - role: yuriyguts.xgboost

License
-------

MIT

Author Information
------------------

Yuriy Guts ([https://github.com/YuriyGuts](https://github.com/YuriyGuts)).

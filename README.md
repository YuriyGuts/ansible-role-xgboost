yuriyguts.xgboost
=================

An Ansible role to install XGBoost on Linux.

Requirements
------------

* This role assumes that the user on the target system can install Python packages without `sudo`. If this is not the case, add `become: yes` to the role parameters in your playbook.
* `pip` on the target system.

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

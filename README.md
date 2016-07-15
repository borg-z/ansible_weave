Role Name
=========

Collection of utils to install and run [weave](https://www.weave.works/)

Requirements
------------

Requires Ansible 2.0 or higher.

Role Variables
--------------

Depends on the specific command being run.
Include
   * `paths.weave`  (path to `weave` command, probably `/usr/local/bin/weave`.
   * `weave_name` (parameter passed in, probably for get_container_ip_addr.yml`



Dependencies
------------

Probably docker :-)

Example Playbook
----------------

    - hosts: foo
      roles:
         - role: dieswaytoofast.ansible_weave

License
-------

BSD

Author Information
------------------

Mahesh Paolini-Subramanya (@dieswaytoofast)

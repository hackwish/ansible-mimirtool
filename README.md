Ansible Mimirtool
=========

This role install Mimirtool for Linux Debian based and Mac based systems.

Requirements
------------

- Linux Debian based system
- MacOS. On Silicon ARM based requires Rosetta.
- Ansible

Role Variables
--------------

NaN

Dependencies
------------

NaN

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

Build ByDefault.

Test
----

``ansible-playbook tests/test.yml -i tests/inventory --syntax-check``

Solo Run
--------

``ansible-playbook tests/test.yml -i tests/inventory``
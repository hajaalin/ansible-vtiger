ansible-vtiger
=========

Installs Vtiger (https://www ...) source code and templates configuration files. The source code can be retrieved from a local archive file (default is the official Booked distribution), a local directory, or a Git repository. The latter two are useful if you want to make custom modifications to the source code.

Requirements
------------

Apache, MySQL and PHP (see Dependencies).

Role Variables
--------------

See defaults/main.yml.

Dependencies
------------
This role has been tested with the following:
- geerlingguy.apache (version: 1.7.2)
- geerlingguy.mysql (version: 2.1.0)
- geerlingguy.php (version: 2.0.3)



Example Playbook
----------------

An example of how to use this role can be found in https://github.com/hajaalin/vtiger-deploy.

License
-------

BSD

Author Information
------------------

Harri Jäälinoja

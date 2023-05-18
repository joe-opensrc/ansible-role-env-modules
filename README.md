Role Name
=========

Installs Modules from Github: 
  - https://github.com/cea-hpc/modules

Requirements
------------

Target host OS needs to be openSUSE(leap)


Role Variables
--------------

See defaults/main.yml.

That you might want to override: 
  modules_version: "5.3.0"
  modules_root_prefix: "/opt/soft/host"
  modules_sys_user: "modules"

Dependencies
------------

  Currently only requires ansible builtin modules

Example Playbook
----------------

  TODO: add harnes github url

License
-------

GPLv2

Author Information
------------------

Joe OpenSrc


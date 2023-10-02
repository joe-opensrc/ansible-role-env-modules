Role Name
=========

Installs Modules from Github: 
  - https://github.com/cea-hpc/modules

Specifically:
  - https://github.com/cea-hpc/modules/releases/download/v5.3.0/modules-5.3.0.tar.gz

Requirements
------------

Target host OS needs to be openSUSE(leap)


Role Variables
--------------

See defaults/main.yml.

The following variables are those you may want to override: 
```
  modules_version:     "5.3.0"
  modules_root_prefix: "/opt/soft"
  modules_sys_user:    "modules"
```

Dependencies
------------

  Currently only requires ansible builtin modules

Example Playbook
----------------

  TODO: add harness github url

License
-------

GPLv2

Author Information
------------------

Joe OpenSrc

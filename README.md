[![Build Status](https://travis-ci.org/cimon-io/ansible-role-imagemagick.svg?branch=master)](https://travis-ci.org/cimon-io/ansible-role-imagemagick)

ImageMagick Ansible Role
=========

Install ImageMagick from source

Requirements
------------

None.

Role Variables
--------------

```
imagemagick_version: "7.1.0"

imagemagick_configure_options: ""
imagemagick_install_path: "/opt/imagemagick"
imagemagick_source_path: "/usr/local/src"

imagemagick_optional_dependencies: []
```

Dependencies
------------

None.

Example Playbook
----------------

```
- hosts: servers
  become: true
  roles:
    - { role: cimon-io.imagemagick, imagemagick_version: '7.1.0"' }
```

License
-------

MIT

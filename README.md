Role of installing ImageMagick
=========

ImageMagick ansible galaxy role.

Requirements
------------

None

Role Variables
--------------

* imagemagick_version  
ImageMagick version

Dependencies
------------

None

Example Playbook
----------------

```yml
---
- hosts: all
  become: true
  roles:
    - { role: galaxy-imagemagick, imagemagick_version: 6.7.8.9 }
```

License
-------

BSD

Author Information
------------------

[Daisuke Maeda](https://github.com/dmae3 "Daisuke Maeda")

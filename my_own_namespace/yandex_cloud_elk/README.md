# Ansible Collection Create File - my_own_namespace.yandex_cloud_elk
=========

This collection contains a role that works with the module for creating a file with any content

Role Variables
--------------

|vars|descriptions|
|---------|-------------------|
| file_pathm |Path to the file, where it should be created with file name |
| file_content |The contents of the file that need to be placed in it |


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
- name: Create file
  hosts: localhost
  roles:
    - my_own_namespace.yandex_cloud_elk.create_file
```

License
-------

GPL-2.0-or-later

Author Information
------------------

Arutyun Galustyan

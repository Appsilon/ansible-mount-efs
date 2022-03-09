Mount EFS
=========

Role used to mount EFS on EC2 instances.

[![CI](https://github.com/Appsilon/ansible-mount-efs/workflows/CI/badge.svg)](https://github.com/Appsilon/ansible-mount-efs/actions/workflows/ci.yml)
[![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-appsilon.mount_efs-blue.svg)](https://galaxy.ansible.com/appsilon/mount_efs)

Requirements
------------

* `curl` (will be installed)

Role Variables
--------------

* `aws_region`
* `efs_az`
* `efs_mount_dir`
* `efs_file_system_id`

Dependencies
------------

None

Example Playbook
----------------

```yaml
- hosts: all
  roles:
     - mount-efs
```

License
-------

MIT

Author Information
------------------

[`Appsilon`](https://appsilon.com/)

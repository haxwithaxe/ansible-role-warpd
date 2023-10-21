warpd
=====

Installs warpd.

Requirements
------------

This requires the `checkinstall` and `git` executables to be in `root`'s `PATH`.

Role Variables
--------------

- `warpd_git_version` - The git tag, branch, or commit to install. Defaults to ``v1.3.7-windows-alpha``.
- `warpd_git_repo` - The URL of the warpd git repo. Defaults to ``https://github.com/rvaiya/warpd.git``.


Dependencies
------------

There are no dependencies on other roles or collections.


Example Playbook
----------------

Install warpd from the ``master`` branch.

    - hosts: all
      roles:
         - role: haxwithaxe.warpd
           vars:
             warpd_git_version: master


License
-------

GPLv3


Author Information
------------------

Created by [haxwithaxe](https://github.com/haxwithaxe)

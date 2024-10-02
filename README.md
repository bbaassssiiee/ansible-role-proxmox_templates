proxmox_templates
=========

Create Proxmox 'templates' (VM base images) on local-lvm.

Requirements
------------

A running ProxMox instance or cluster.

Role Variables
--------------

`defaults/main.yml` has a list of images with their properties, one for Ubuntu, one for Debian.

Dependencies
------------

Collection: `community.general`.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: pve
      roles:
         - { role: bbaassssiie.proxmox_templates }

License
-------

MIT

Author Information
------------------

http://github.com/bbaassssiiee

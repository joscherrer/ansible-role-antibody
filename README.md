Antibody
=========

This role installs antibody

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

```
antibody_force_install: false
antibody_install_version: "4.2.0"
```

Dependencies
------------

geerlingguy.git

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      vars:
        antibody_force_install: true
        antibody_install_version: "4.2.0"
      roles:
         - ansible-role-antibody

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).

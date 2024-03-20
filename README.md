Role Name
=========

An Ansible role for live patching RHEL 7,8,9 systems and configuring them for 
automatic kernel patching.

Requirements
------------

Server must be subscribed to RHEL repositories

Role Variables
--------------
none

Dependencies
------------
none


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: all
  tasks:
    ansible.builtin.include_role:
      name: livepatch
```


License
-------

MIT

Author Information
------------------

Hugo F. Gonzalez <hgonzale@redhat.com>

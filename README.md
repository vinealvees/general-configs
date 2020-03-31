general-configs
=========

This role setting some basics configures at Cisco Switch like Banner, SSH, Password Encryption, Time, Domain and HTTP Server.

Requirements
------------

Role tested in Ansible 2.9.2, Python 2.7, Cisco IOS

Dependencies
------------

This role depends that a user that do login into switch and already been at enable mode.
Otherwise you will need use ansible_become and ansible_become_method like this:
https://docs.ansible.com/ansible/latest/network/user_guide/network_best_practices_2.5.html

Example Playbook
----------------

```
- name: General Configurations
  hosts: sw_net_auth
  roles:
    - general-configs
```

License
-------

BSD

Author Information
------------------

Github: [vinealvees](#https://github.com/vinealvees/)
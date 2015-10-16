Ansible
=========

Role to install Ansible from git clone and manage ansible.cfg.
By default no variables required.


Role Variables
--------------

defaults/main.yml

```
ansible_inst:
 dir: /opt/ansible
 add_evn_setup_hack_sys_wide: True

ansible_cfg: ansible.cfg.j2
```


Example Playbook
----------------

```
- hosts: servers
  roles:
     - ansible
```


License
-------

MIT


Author Information
------------------

Tal Lannder

tallannder@gmail.com

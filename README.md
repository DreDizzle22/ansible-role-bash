Ansible Role for Bash
=========

This role is for installing bash via homebrew and setting it as the default shell.

Requirements
------------
- Ansible 2.8 or later

Role Variables
--------------
none

Dependencies
------------
none


Usage
----------------
#### Include in playbook
    - hosts: localhost
      name: "Configuring your shell to use bash!"
      roles:
         - role: dredizzle22.bash

#### Install independently
`ansible-pull -U https://github.com/DreDizzle22/ansible-role-bash.git`

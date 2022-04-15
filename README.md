lnd
=========

An ansible role that compiles lnd from source.


Requirements
------------

At this moment only tested on Debian/Ubuntu.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

Requires [gantsign.golang](https://galaxy.ansible.com/gantsign/golang)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

  - hosts: lnd
    roles:
      - role: gantsign.golang
        golang_gopath: '$HOME/workspace-go'
      - nodi.lnd

License
-------

MIT
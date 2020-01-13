Install Docker
==============

This role install Docker on a Debian machine.

Requirements
------------

None.

Role Variables
--------------

```yaml
# Install Docker CE CLI
install_docker_ce_cli: false

# Install containerd.io
install_containerd_io: false
```

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: mmartinello.docker }

License
-------

BSD

Author Information
------------------

Mattia Martinello - mattia@mattiamartinello.com

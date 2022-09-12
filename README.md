Install Podman via Ansible
=========

Ansible-Podman installation would install the Podman on cross-platform operating systems, like: Ubuntu, CentOS, and Rockylinux

Requirements
------------

It would work on the every cloud platform such as Amazon EC2, ArvanCloud Abrak, and so on.

Role Variables
--------------

Variables only set on the single variables file on the `/vars` path. It is included some variables that containing _key repository url_, and _repository url_

Dependencies
------------
None.

Example Playbook
----------------
```yml
    - hosts: servers
      roles:
         - { role: m0rphix000.install-podman }
```

License
-------
None.

Author Information
------------------

This role was created in 2022 by MohRez Fadaei.
google-chrome
=============

This role install the latest version available of Google Chrome

Requirements
------------

No requeriments.

Role Variables
--------------

channel: [ stable, beta, unstable ] - Defines waht versions will be installed.


Dependencies
------------

No dependencies.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: mhalano.google-chrome, channel: [ stable, beta ]}

License
-------

MIT

Author Information
------------------

My name is Marcos H. Alano. This is my fifth role published on Ansible Galaxy. I wrote a lots of roles and I will porting one by one. Is all roles related to desktop applications (may be a few server applications in the future) because my plan is automatize the post-installation of my computer.

To Do
-----

* Support macOS
* Do tests on RPM-based distributions
* Do tests on Debian distribution
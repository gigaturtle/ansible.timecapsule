Timecapsule
=========
[![Build Status](https://travis-ci.org/gigaturtle/ansible.timecapsule.svg?branch=master)](https://travis-ci.org/gigaturtle/ansible.timecapsule)

This role will configure an Ubuntu host to act as a timecapsule target via AFP.

Requirements
------------

Tested with Ubuntu 16.04. This role installs the following packages with apt:
- netatalk
- libc6-dev
- avahi-daemon
- libnss-mdns

Role Variables
--------------

backup_dir: Specify the absolute path where backup files will be stored.

Dependencies
------------

This does not depend on any other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: backup-servers
      roles:
         - ansible.timecapsule

License
-------

Apache

Author Information
------------------

[github.com/gigaturtle](https://github.com/gigaturtle)

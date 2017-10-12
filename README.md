[![Build Status](https://travis-ci.org/CSCfi/ansible-role-arc-frontend.svg)](https://travis-ci.org/CSCfi/ansible-role-arc-frontend)
ansible-role-arc-frontend
=========

Ansible role that installs and configures a Nordugrid ARC Grid Frontend 

Requirements
------------


Role Variables
--------------

There are many variables to be set.

See tasks/main.yml , templates/arc.conf.j2 and defaults/main.yml 

 - arc_frontend_nis: false
 - add_slurm_accts: false

These services are set to disabled:
<pre>
arc_frontend_services:
 - arched
</pre>

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-arc-frontend }

License
-------

MIT

Author Information
------------------


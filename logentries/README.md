Role Name
=========

Install and configuring logging to the logentries.com service.

Requirements
------------


Role Variables
--------------

    logentries_repo: 'deb http://rep.logentries.com/ precise main'
    logentries_account_key:

Dependencies
------------


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: logentries, logentries_account_key: dsfhkjdshkfhdjfs }

License
-------

BSD

Author Information
------------------

Mark Phillips <mark@devopsguys.com>
https://flyvictor.atlassian.net/wiki/display/DEV/Orchestration+with+Ansible

Role Name
=========

This role install a cronjob that repeatedly pulls the latest version of the master branch of git remote(s).

Role Variables
--------------

user: the user that should be running the update cronjob
scripts dir: where the update cronjob script should be saved
repositories: which repositories should be updated.

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

The Wikidata Team

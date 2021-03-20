Vacations
=========

After having my pals telling me for a week to stop working during holidays, I realized that I needed a module to force me to halt. Thus, I created this role to lock you out of your systems for the vacations duration.

Requirements
------------

Requires 'at' extra module.

Role Variables
--------------

vacations: Holidays duration in days. 

Dependencies
------------

It depends on having the 'at' command in the remote systems


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - { role: ieguiguren.vacations, vacations: 42 }

License
-------

BSD

Author Information
------------------

Contact me as donosor00 in the gmail.com servers

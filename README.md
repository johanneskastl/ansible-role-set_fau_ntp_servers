set_fau_ntp_servers
=========

Use the fau ntp servers

Requirements
------------

None.

Role Variables
--------------

`chronyd_service`: The name of the chronyd service, by default 'chronyd'.
`list_of_ntp_servers`: A list of ntp servers.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: johanneskastl.set_fau_ntp_servers }

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.

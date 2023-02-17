![Ansible Lint](https://github.com/johanneskastl/ansible-role-set_fau_ntp_servers/workflows/Ansible%20Lint/badge.svg)

set_fau_ntp_servers
=========

Use the ntp servers from Friedrich-Alexander-University Erlangen-Nuremberg (fau.de)

Requirements
------------

Chrony (SLES15, openSUSE Leap 15.x, openSUSE MicroOS or openSUSE Leap Micro) or ntpd (SLES12) need to be installed.

Role Variables
--------------

- `chronyd_service`: The name of the chronyd service, by default 'chronyd' (only used on SLES15 or newer).
- `ntpd_service`: The name of the ntpd service, by default 'ntpd' (only used on SLES12).
- `list_of_ntp_servers`: A list of ntp servers.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: 'johanneskastl.set_fau_ntp_servers'

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.

postfix
=======

An Ansible Role that configures Postfix on Debian/Ubuntu.


Requirements
------------

None.


Role Variables
--------------

    # Configuration options in /etc/postfix/main.cf:
    postfix_config:
      relayhost: 127.0.0.1

    # Aliases
    postfix_aliases:
      postmaster: root


Dependencies
------------

None.


Example Playbook
----------------

    - hosts: all
      roles:
        - { role: postfix }


License
-------

MIT

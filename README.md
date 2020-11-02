sysctl_config
=========

SYSctl role configuration


Role Variables
--------------

Although you need to read `defaults/main.yml` variables can be passed in as:
```
sysctl_settings:
  "net.ipv4.tcp_syncookies": 1
```

Depending on the OS and the needs you have, you may want to consult the relevant CIS guides.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: frite.sysctl_config, }

License
-------

MIT

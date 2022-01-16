Role Name
=========
Nodejs

Requirements
------------

Role Variables
--------------
```
user: root 
```
```
nvm_version: 'v0.39.1'
```
```
node_version: v16.13.2
```

Example Playbook
----------------

    - hosts: localhost
      connection: local
      roles:
         - { role: ck3mp3r.nodejs, user: bob, nvm_version:v0.39.1, node_version: v16.13.2 }

License
-------

MIT

Author Information
------------------

Christian Kemper | kemper.buzz

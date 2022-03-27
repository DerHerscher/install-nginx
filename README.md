Install Nginx
=========

This Role installs nginx as an reverse proxy

Requirements
------------

You need to generate an dhparams.pem file and place it in /files/etc/ssl/private/ beforee using this role.
For that you can use ```openssl dhparam -out dhparams.pem 4096```

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - install-nginx

License
-------

MIT
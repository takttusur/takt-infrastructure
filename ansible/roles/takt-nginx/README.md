takt-nginx
=========

The role fetch and starts all applications for TAKT website

Requirements
------------

Role Variables
--------------
`takt_host_url` - Endpoint URL to access the website

Dependencies
------------

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
```yaml
- hosts: servers
  become: true
  roles:
    - role: takt-nginx
```

License
-------
MIT

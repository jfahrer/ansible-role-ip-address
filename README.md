Role Name
=========

This role registers the nodes first private ip address as a fact. You can access it via `internal_ipv4_address`.

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yaml
    - hosts: servers
      roles:
        - jfahrer.core-utils
```

License
-------

MIT

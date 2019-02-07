Redis Role
=========

Installs and configures a simple Redis service


----------------

```

# Vars

# False values install the default version fetched by APT
# Note - that you may need to do some dependency resolution on your own in this case
redis_version: false
redis_listen_port: 6379
redis_bind_interface: '0.0.0.0'

#   requirements.yml
#
#   Example
# - src: https://github.com/ergontech-ansible-roles/redis
#   version: master
#   name: redis
```

License
-------

[MIT](LICENSE)
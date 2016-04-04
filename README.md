Docker role [![ansible role](https://img.shields.io/badge/ansible-role-orange.svg)](https://galaxy.ansible.com/anarcher/docker/)
-----------

Installs Docker.

## Requirements

This role requires Ansible 1.4 or higher.


## Role Variables

| Name           | Default | Description |
|----------------|---------|-------------|
| docker_version | none    |             |
| docker_opts    | none    |             |
| docker_users   | ubuntu  |             |
| docker_labels  |         |             |
| docker_registries  |         | { "host" : "<host>", "auth" : "<auth>" , "email" : "<email" } |

```
docker_version:
docker_opts:
docker_labels: []
docker_users: []
docker_registries: []
```

## Dependencies

- retr0h.logrotate

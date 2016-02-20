Docker role [![ansible role](https://img.shields.io/badge/ansible-role-orange.svg)]()
-----------

Installs Docker.

## Requirements

This role requires Ansible 1.4 or higher.


## Role Variables

| Name           | Default | Description |
|----------------|---------|-------------|
| docker.version | none    |             |
| docker.opts    | none    |             |
| docker.users   | ubuntu  |             |

```
docker:
    version: ""
    opts: ""
    users:
        - "ubuntu"
```

## Dependencies

- retr0h.logrotate
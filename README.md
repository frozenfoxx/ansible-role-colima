# ansible-role-colima

Ansible role to install and manage Colima

# Requirements

- macOS
- [Homebrew](https://brew.sh)

# Variables

- `colima_user`: user to run startup with (default `user`)

# Usage

```
- hosts: servers
  roles:
    - { role: frozenfoxx.colima }
```

# License

Apache-2.0

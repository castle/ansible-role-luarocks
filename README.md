# Ansible Role: luarocks

[![Build Status](https://travis-ci.org/AttestationLegale/ansible-role-luarocks.svg?branch=master)](https://travis-ci.org/AttestationLegale/ansible-role-luarocks) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-luarocks-blue.svg)](https://galaxy.ansible.com/AttestationLegale/luarocks/)

The luarocks role allows you to install lua rocks.


## Requirements

None

## Role Variables

For a complete list of variables, see `default/main.yml`.

    luarocks_packages: []
    luarocks_group_packages: []
    luarocks_host_packages: []

## Dependencies

None

## Example Playbook

```yaml
---
  - hosts: all
    roles:
      - luarocks
```

## License

MIT / BSD

## Author Information

This role was created in 2016 by [ALG](https://www.attestationlegale.fr)

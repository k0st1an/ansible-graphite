# ansible-graphite

[![Ansible Galaxy](https://img.shields.io/badge/galaxy-k0st1an.graphite-blue.svg?style=flat)](https://galaxy.ansible.com/k0st1an/graphite/)

Role for deploying Graphite

# Dependencies

- supervisor

## Example Playbook

```
- hosts: localhost
  remote_user: root
  roles:
     - k0st1an.graphite
```

## Todo

- `supervisor` => `systemd`

## License

MIT


## Author Information

- Author: Konstantin Kruglov
- GitHub: https://github.com/k0st1an
- Contact: kruglovk@gmain.com

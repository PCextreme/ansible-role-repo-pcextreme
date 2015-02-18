# Ansible Role: PCextreme Repository

PCextreme Linux Software Repository

## Supported platforms

```
CentOS 6 & 7
Ubuntu 14.04
```

## Requirements

None

## Role Variables

Repository components (main, updates, testing):

```
repo_pcextreme_main: true
repo_pcextreme_updates: true
repo_pcextreme_testing: false
```

## Dependencies

None

## Example Playbook

```
- hosts: servers
  roles:
    - { role: pcextreme.repo-pcextreme }
```

## License

MIT

## Author Information

Created by [Attila van der Velde](https://github.com/vdvm)

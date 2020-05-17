# VLC

This role handles installing VLC on a Fedora system.

## Requirements

The hosts you are targeting should have the following packages:

- python >= 2.6
- python-dnf

## Role Variables

None

## Dependencies

- `jaredhocutt.rpmfusion`

## Example Playbook

```yaml
- hosts: servers
  roles:
    - role: jaredhocutt.vlc
```

## License

MIT

## Author Information

Jared Hocutt (@jaredhocutt)

# Role for installing emacs

Ansible role to make sure emacs is installed. Does no more, no
less. You should take care of your emacs.d yourself.

## Requirements

None.

## Role Variables

None required.

### `emacs_packages`

Optionally the role default emacs package list can be overriden with
this variable set in your inventory.

## Dependencies

None.

## Example Playbook

```yaml
  - hosts: localhost
    vars:
    roles:
       - agoloncser.emacs
```

## License

BSD

## Author Information

[@agoloncser](https://github.com/agoloncser)


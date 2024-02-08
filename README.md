# Role for installing emacs

[![Molecule testing](https://github.com/agl4/ansible-role-emacs/actions/workflows/ci.yml/badge.svg)](https://github.com/agl4/ansible-role-emacs/actions/workflows/ci.yml)

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
       - agl4.emacs
```

## License

BSD

## Author Information

[@agl4](https://github.com/agl4)


# virtualenv

Ansible role to install pip (python modules)

## Installation

```yaml
   ansible-galaxy install zerodowntime.virtualenv
```

## Requirements

This role requires Ansible 2.5 or higher.

Supported platforms:

```yaml
  platforms:
    - name: EL
      versions:
        - 7
    - name: Ubuntu
      versions:
      - trusty
      - xenial
```

## Example Playbook

```yaml
    - hosts: all
      become: true
      roles:

      - role: zerodowntime.virtualenv
```

## License

[Apache License 2.0](LICENSE)

## Support

ansible@zerodowntime.pl

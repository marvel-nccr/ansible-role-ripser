[![Build Status](https://travis-ci.org/marvel-nccr/ansible-role-ripser.svg?branch=master)](https://travis-ci.org/marvel-nccr/ansible-role-ripser)

# Ansible Role: marvel-nccr.ripser

An Ansible role that installs [Ripser](https://github.com/Ripser/ripser) on Ubuntu.

## Installation

`ansible-galaxy install marvel-nccr.ripser`

## Role Variables

See `defaults/main.yml`

## Example Playbook

```yaml
- hosts: servers
  roles:
  - role: marvel-nccr.ripser
```

## Tests

This role uses [Molecule](https://molecule.readthedocs.io/en/latest/#) and
Docker for tests. Once Docker is installed, run tests using

```bash
pip install -r requirements.txt
molecule test
```

## License

MIT

## Contact

Please direct inquiries regarding Quantum Mobile and associated ansible roles to the [AiiDA mailinglist](http://www.aiida.net/mailing-list/).

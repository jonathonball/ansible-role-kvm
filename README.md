# Ansible Role: kvm

[![Build Status](https://travis-ci.org/jonathonball/ansible-role-kvm.svg?branch=main)](https://travis-ci.org/jonathonball/ansible-role-kvm)

## Requirements

See `requirements.txt`.

## Role Variables

- `kvm_user` user permitted to run kvm tasks on target hosts

## Dependencies

None

## Example Playbook

    - hosts: servers
      roles:
        - jonathonball.kvm

# License

MIT

## Author Information

[Jon Ball](mailto:jonathon.ball@gmail.com)

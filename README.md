# Ansible role: Docker for ARM

[![CI](https://github.com/blalop/ansible-role-docker_arm/workflows/CI/badge.svg?event=push)](https://github.com/blalop/ansible-role-docker_arm/actions?query=workflow%3ACI)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-blalop.docker_arm-B62682.svg)](https://galaxy.ansible.com/blalop/docker_arm)


A heavily opinionated role to install Docker using the convenience script and docker-compose using pip. This role is intended to be used in ARM-based devices like Raspberry Pi although still being runnable on x64 hosts.

## Requirements

No special requirements. Use it in your playbook like this:

```
- hosts: all
  roles:
    - blalop.docker_arm
```

## Testing

Test the role via molecule:

```
pip install molecule
molecule test
```

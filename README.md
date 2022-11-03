# Install Packer

Ansible role to install the Packer using APT for either Ubuntu 16.04 (xenial), 18.04 (bionic) or 20.04 (focal).

## Installation

`ansible-galaxy install richeney.ansible-install-packer`

## Example Playbook

```yaml
- hosts: all
  roles:
    - richeney.ansible-install-packer
```

## Requirements

None.

## Dependencies

None.

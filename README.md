# Install Packer

Ansible role to install the Packer using APT for either Ubuntu 20.04 (focal), 22.04 (jammy), or 24.04 (noble).

Updated to handle ARM for the new Surface 7 Laptop.

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

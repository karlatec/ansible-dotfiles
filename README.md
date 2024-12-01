# ansible-dotfiles

Simple role to manage my dotfiles from [karlatec/dotfiles](https://github.com/karlatec/dotfiles).

Used as part of other Ansible roles and playbooks.

## Requirements

As in [requirements.txt](https://github.com/karlatec/ansible-dotfiles/blob/main/requirements.txt).

## Dependencies

Following packages need to be installed in the target system:

* git
* vim

## Example playbook

As in [molecule/default/converge](https://github.com/karlatec/ansible-dotfiles/blob/main/molecule/default/converge.yml)

```yaml
---
- name: Converge
  hosts: all
  gather_facts: true
  roles:
   - role: ansible-dotfiles
```

# Ansible Task: Upgrade Arch Linux System

This reusable Ansible task upgrades Arch Linux.

## Requirements

- Ansible 2.9+
- Target system running Arch Linux or an Arch-based distribution
- Root/sudo privileges on the target system
- Internet connectivity for package downloads

## Usage

Example inclusion in a playbook:

```yaml
- name: Install Arch Linux core packages
  include_tasks: tasks/task-arch-Syu.yml
```

## Dependencies

This module has no external dependencies beyond the core Ansible requirements.

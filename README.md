# Ansible Role: timezone

Setup timezone on Linux.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values:

    timezone: Etc/UTC

## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - Akman.timezone

*Inside `vars/main.yml`*:

    timezone: Europe/Kaliningrad

## License

MIT / BSD

## Author Information

This role was created in 2017 by Alexander Kapitman

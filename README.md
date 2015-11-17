# Ansible role: backports

An Ansible Role that adds the backports repository to Debian hosts

## Requirements

None

## Dependencies

None

## Example Playbook

    ---
    - hosts: all
      sudo: yes

      roles:
         - { role: jgeusebroek.backports, tags: ["backports"] }

## Example Variables

    # You can configure your prefered backports mirror
    backports_mirror_url: 'http://ftp.nl.debian.org/debian'

## License

MIT / BSD

## Author Information

This role was created in 2015 by [Jeroen Geusebroek](http://jeroengeusebroek.nl/).
[![Build Status](https://travis-ci.org/jgeusebroek/ansible-role-backports.svg?branch=master)](https://travis-ci.org/jgeusebroek/ansible-role-backports)
[![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-jgeusebroek.backports-blue.svg)](https://galaxy.ansible.com/jgeusebroek/backports)

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

2015 - 2019 by [Jeroen Geusebroek](http://jeroengeusebroek.nl/).
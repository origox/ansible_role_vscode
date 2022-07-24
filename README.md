# Ansible-role: ansible_role_vscode
[![CI](https://github.com/origox/ansible_role_vscode/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/origox/ansible_role_vscode/actions/workflows/ci.yml)

An Ansible role to install and configure vscode

## Requirements

None.

## Role Default Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    git_config:
      <section>:
        <key>: <value>

## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - role: 
            src: https://github.com/origox/ansible_role_vscode 



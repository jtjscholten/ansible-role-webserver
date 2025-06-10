# Ansible Role: Webserver

Deze Ansible role installeert:
- Apache2
- PHP
- php-mysql

## Requirements

Debian-based systeem (bijv. Ubuntu, Debian)

## Role Variables

Geen (nog)

## Dependencies

Geen

## Example Playbook

```yaml
- hosts: webservers
  become: true
  roles:
    - jeroenscholten.webserver

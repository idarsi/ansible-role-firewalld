ANSIBLE ROLE FIREWALLD
======================

**COPYRIGHT** 2024 Arsi Atomi  
**LICENSE** GPL-2.0-or-later  
**AUTHORS**

- Arsi Atomi <arsi@atomi.sh>

Overview
--------

This ansible role is meant for easier firewalld management specially with ipsets.

Uses only firewall-cmd command, not any firewalld ansible modules.

Requirements
------------

Control machine:
- Ansible version 2.11 or later

Target machine:
- DNF package manager

Code Quality
------------

This project adheres to the [Ansible Lint](https://ansible-lint.readthedocs.io) **production** profile, ensuring high-quality and production-ready configuration management.

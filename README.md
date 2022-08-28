# My Macbook Setup

**THIS IS A WORK IN PROGRESS**

Automatic configuration and installation of tools for my Macbook using Ansible:

- [elliotweiser.osx-command-line-tools](https://github.com/elliotweiser/ansible-osx-command-line-tools) ansible role to install cli tools
- [geerlingguy.mac](https://github.com/geerlingguy/ansible-collection-mac) collection of roles to manage a Mac
- [ansible-role-pip](https://github.com/Allaman/ansible-role-pip) installs pip packages

## Bootstrap Process

- `xcode-select --install`
- `pip3 install --upgrade pip`
- `pip3 install --user ansible`

## Run Ansible

Run Ansible with the provided Makefile:

- `make install` to download required ansible roles
- `make configure` to run `ansible-playbook` (sudo password required)

## Extras / Manual Install

Read through [extras.md](./extras.md)

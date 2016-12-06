# Ansible roles

This is a work in progress.

## Usage

## Setup a server

```bash
$ ansible-playbook playbooks/b1-setup.yml --ask-vault-pass --ask-become-pass
```

## Configure a website

```bash
$ ansible-playbook playbooks/b1-www.yml --ask-vault-pass --ask-become-pass
```

## Using Vaults

[Documentation](http://docs.ansible.com/ansible/playbooks_vault.html)

```bash
$ ansible-vault create vaults/b1.yml
$ ansible-vault edit vaults/b1.yml
$ ansible-vault rekey vaults/b1.yml
```

# Ansible roles

## Usage

## Setup a server

```bash
$ ansible-playbook playbooks/b1.tb.io/setup.yml --ask-vault-pass --ask-become-pass
```

## Mattermost

### Install

```bash
$ ansible-playbook playbooks/b1.tb.io/mattermost.yml --ask-vault-pass --ask-become-pass
```

### Upgrade

```bash
$ ansible-playbook playbooks/b1.tb.io/mattermost-upgrade.yml --ask-vault-pass --ask-become-pass
```

### ZNC

```bash
$ ansible-playbook playbooks/b1.tb.io/znc.yml --ask-vault-pass --ask-become-pass
```

## Using Vaults

[Documentation](http://docs.ansible.com/ansible/playbooks_vault.html)

```bash
$ ansible-vault create vaults/b1.yml
$ ansible-vault edit vaults/b1.yml
$ ansible-vault rekey vaults/b1.yml
```

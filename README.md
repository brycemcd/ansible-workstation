# Ansible Personal System

> To configure and maintain my workstation in a consistent state

## Pre Ansible

An assumption that a brycemcd user was created at install time

### Grant sudo without Password (enough rope to hang myself with)

```bash
sudo visudo
brycemcd ALL=(ALL:ALL) NOPASSWD:ALL
```

### Install Ansible

```bash
$ sudo apt-get update
$ sudo apt-get install software-properties-common
$ sudo apt-add-repository ppa:ansible/ansible
$ sudo apt-get update
$ sudo apt-get install ansible
```
## SERMO Specific

I work from home a lot and naturally some of my tasks are more
convenient from my own desktop. These tasks are distinct from tasks
that require elevated machine privileges. Playbooks that are specific to
SERMO are in a repo owned by SERMO in Gitlab. Those playbooks can be
installed separately or as a submodule of this repo.

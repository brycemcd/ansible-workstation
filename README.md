# Ansible Personal System

> To configure and maintain my workstation in a consistent state

## Pre Ansible

An assumption that a brycemcd user was created at install time

### Grant sudo without Password (enough rope to hang myself with)

`sudo visudo`
`brycemcd ALL=(ALL:ALL) NOPASSWD:ALL`

### Install Ansible

$ sudo apt-get update
$ sudo apt-get install software-properties-common
$ sudo apt-add-repository ppa:ansible/ansible
$ sudo apt-get update
$ sudo apt-get install ansible

# Hobo.Ansible.Docker
Ansible role to install docker and optionally add the connected user to the `docker` group

## Requirements
* [Hobo.Ansible.Common](https://github.com/hobointhecorner/Hobo.Ansible.Common)

## Install Role
From inside your playbook roles directory:
`git submodule add [-b <branch or tag>] https://github.com/hobointhecorner/Hobo.Ansible.Docker.git`

## Variables
| Name                | Type | Required | Default | Desctiption |
|---------------------|------|----------|---------|-------------|
| docker_add_to_group | bool | No       | true    | Add the connected user to the `docker` group on the host |

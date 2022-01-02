# Hobo.Ansible.Docker
Ansible role to install docker and optionally add the connected user to the `docker` group

## Requirements
* [Hobo.Ansible.Common](https://github.com/hobointhecorner/Hobo.Ansible.Common)

## Install Role
### Ansible Galaxy
[Ansible Galaxy](https://galaxy.ansible.com/docs/using/installing.html) can be used to install the role:
`ansible-galaxy install git+https://github.com/hobointhecorner/Hobo.Ansible.Docker.git[,<branch or commit hash>]`

### Git submodule
From inside your playbook roles directory:
`git submodule add [-b <branch or tag>] https://github.com/hobointhecorner/Hobo.Ansible.Docker.git`

## Variables
| Name                | Type | Required | Default | Desctiption |
|---------------------|------|----------|---------|-------------|
| docker_add_to_group | bool | No       | true    | Add the connected user to the `docker` group on the host |

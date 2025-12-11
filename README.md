# About
Here are all the Ansible configuration needed to set up and manage game-metrics infrastructure

## Prerequisites
- [Ansible 2.19](https://docs.ansible.com/projects/ansible/latest/installation_guide/intro_installation.html#control-node-requirements)

## First steps
Playbooks here are supposed to be run by `ansible` user. The following steps are required to run playbooks:
1. Please contact project maintainer to receive `ansible` credentials – the .ssh directory content
2. Run
```shell
make ssh_agent
```
to configure the agent with ansible ssh key

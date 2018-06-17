# Vagrant Ansible practice

This repository is for practice learning how to use ansible.
Vagrant is used for deploying virtual machines.

## Ansible

### What is Andible

> Ansible is a radically simple IT automation system. It handles configuration-management,
> application deployment, cloud provisioning, ad-hoc task-execution, and multinode orchestration
> -- including trivializing things like zero-downtime rolling updates with load balancers.

### What do I want to do by Ansible

- Synchronize real setting on server with documents
- Management installed application (e.g. yum, apt-get)
- Deploy conf files
- Update OS user password

## Vagrant

Vagrant provision, restruct, the environment, share the same environment with everyone
in a simple setting.

### Usefull Vagrant modules

```sh
# Add an entry to your /etc/hosts file on the host system.
vagrant plugin install vagrant-hostsupdater
```

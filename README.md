# Example on how to use Ansible to create and configure Keycloak Docker containers

This repository contains a simple example usage of keycloak docker container and ansible together to configure a new client under a newly created keycloak container

create.yml creates a keycloak container based on the dockerfile present under /docker and playbook.yml configures a client in the created container and destroy.yml, destroys the same container.

This is for a local usage using docker and makes use of localhost to launch those containers.

Inventory is also as simple as possible, and not a remote reference using other Docker Daemon URL.

This is also a companion repository of a tutorial at https://ilhicas.com on how to use Ansible to provision keycloak containers.

https://ilhicas.com/2018/08/29/keycloak-in-docker-ansible-configured.html
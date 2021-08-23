# docker-ansible
#### ansible role for docker installation
---
## What's configured in this playbook?
####  The latest Docker CE and Docker Compose will be installed
---
#### NOTE: Ansible-core version is 2.11.4
---
## Installation
##### ansible-playbook -i hosts.ini play.yaml

 - hosts.ini Specify inventory host path 

---
## Variables

- DOCKER_PACKAGES: Packages that required by docker
- DOCKER_CE: Main docker service packages
- DOCKER_COMPOSE_VERSION: Version of docker-compose that will be installed

---
###### [@dwsclass](https://github.com/dwsclass)dws-ops-002-ansible

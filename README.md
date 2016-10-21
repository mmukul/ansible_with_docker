# Ansible with docker

## Requirement

 python >= 2.6
 docker-py >= 1.10.3
 The docker server >= 1.10.3
 
## How to provision containers

* `ansible-playbook container_build.yml`

## Remove containers

* `ansible-playbook container_remove.yml`

## Remove docker images

* `ansible-playbook container_remove-image.yml`




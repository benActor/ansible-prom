# ansible-prom

## Descrption
Ansible playbook designed to deploy and configure docker compose stack for prometheus, grafana and alermanager. playbook operate in, 
- Installing docker
- Installing docker-compose
- configure prometheus, grafana and alertmanager.
- deploy compose file.

## Requirements 
Designed to install services on linux host.

## variables 
Playbook allows some customization of deployed stack with vaiables defined under host_vars/container_host.yml
Prometheus and alertmanager configuration files stored under files.

## Run
> _ansible-playbook -i inventory deploy_prom.yml_

# Manifest files

infra:
1. Zabbix - zabbix_docker-compose.yaml
2. ELK - elk_docker-compose.yaml
3. Honey-mgmt - honey_mgmt_docker-compose.yaml

honey:
1. Honey-client - honey_client_docker-compose.yaml
2. Honey_birtix - honey_bitrix_docker-compose.yaml


# Topology

# Install
ALL VM(VPS)
Ubuntu 22
apt install docker.io docker-compose net-tools jq mc htop 

docker-compose up -d {manifest_role_file}

# Debug

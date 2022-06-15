# zabbix
requiments:
  docker
  docker-compose

zabbix-server run:
  docker-compose -f docker-compose-server-amd64.yaml up -d
  
zabbix-agent-proxy run:
  docker-compose -f docker-compose-proxy-amd64.yaml up -d
  
default login:
  Admin
  zabbix
  

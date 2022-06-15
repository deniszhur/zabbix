# zabbix
requirements:<br>
  docker<br>
  docker-compose<br>
<br>
zabbix-server run:<br>
  docker-compose -f docker-compose-server-amd64.yaml up -d<br>
<br>
zabbix-agent-proxy run:<br>
  docker-compose -f docker-compose-proxy-amd64.yaml up -d<br>
<br>
default login:<br>
  Admin<br>
  zabbix<br>
  

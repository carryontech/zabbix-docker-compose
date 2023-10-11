# Zabbix com Docker Compose :whale:

O arquivo docker-compose.yml que disponibilizamos em nosso Github, foi configurado de forma que o Docker crie 4 containers: 

- zabbix-server |  zabbix-frontend | grafana | mysql 

> Utiilizadas as imagens oficiais do Zabbix, do Grafana e do MySQL. Os links para consulta estão no final deste artigo. 

Ao executar o comando <b>docker-compose up -d </b> o Docker irá subir de forma automática os containers. O Zabbix já estará conectado ao banco de dados MySQL e o Grafana já estará com o plugin do Zabbix instalado.

- Mysql - https://hub.docker.com/_/mysql 
- Zabbix - https://hub.docker.com/u/zabbix
- Grafana - https://hub.docker.com/u/grafana

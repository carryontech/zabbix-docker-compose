Zabbix com Docker Compose

O objetivo deste arquivo é provisionar um ambiento do zabbix em docker, utilizando as imagens oficiais. Alem do zabbix, vamos criar um container para o MYSQL e Grafana.

Ao executar o docker compose vamos subir de forma automatizada o zabbix, conectado no mysql e criando o banco de dados, em seguida será conectado o zabbix frontend e por ultimo o grafana com o plugin do zabbix instalado.

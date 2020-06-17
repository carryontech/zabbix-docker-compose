Zabbix com Docker Compose

O objetivo deste arquivo é provisionar um ambiente do Zabbix em Docker, utilizando as imagens oficiais. Alem do Zabbix, vamos criar um container para o MYSQL e Grafana.

Ao executar o Docker Compose, vamos subir de forma automatizada o Zabbix, conectado ao MySQL, criando o banco de dados. Em seguida, será conectado o Zabbix frontend e por ultimo o Grafana com o plugin do Zabbix instalado.

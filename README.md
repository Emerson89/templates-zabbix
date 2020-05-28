#Objetivo
Monitorar ELB da AWS

#Dependencias

Zabbix 3.0

#Como utilizar

Verificar se o script cloudwatch-zabbix.py está no diretório /usr/lib/zabbix/externalscripts

Dar permissão de execução para o script

    chmod +x /usr/lib/zabbix/externalscripts/cloudwatch-zabbix.py

#Importar o template no zabbix

Ir em configurações, templates e clique em importar



Clique em Choose File e escolha o template-elb.xml





Clique em importar




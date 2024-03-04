# Zabbix-Server en Docker

Este docker-compose utiliza las siguientes variables:

<note>ZABBIX_HOME: ruta donde se guardan los datos dentro del servidor fisico, ej: /Zabbix-Home </note>

<note>URL_ZABBIX_REPORT: normalmente es la IP la del propio servidor donde se despliega, la misma va en la siguiente notacion: http://<FQDN>o<IP>:10053/report</note>

<note>IP_AUTH: IPs autorizadas a consultar los reportes de Zabbix</note>

<note>MYSQL_ROOT_PASSWORD: Contraseña de usuario root de la BD</note>

<note>MYSQL_PASSWORD: Contraseña de la BD</note>

Se adjunta un archivo de variables (stack.env) para utilizarlo como ejemplo de uso
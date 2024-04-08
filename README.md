# Zabbix-Server en Docker

Este docker-compose utiliza las siguientes variables:

|  Parámetro          |   Función                                                                                                                |
|:--------------------|:-------------------------------------------------------------------------------------------------------------------------|
| ZABBIX_HOME         | Ruta donde se guardan los datos dentro del servidor físico  ej: /Zabbix-Home                                             |
| URL_ZABBIX_REPORT   | IP del propio servidor Zabbix donde se despliega. La notación es: http://IP_del_servidor_zabbix-web-service:10053/report |
| ZABBIX_HOSTNAME     | Nombre o FQDN declarado en el servidor Zabbix para el proxy                                                              |
| ZABBIX_SERVER       | IP o FQDN del servidor Zabbix                                                                                            |
| MYSQL_ROOT_PASSWORD | Contraseña de usuario root de la BD                                                                                      |
| MYSQL_PASSWORD      | Contraseña de la BD                                                                                                      |
| MYSQL_VERSION       | Versión de contenedor de MySQL. Ejemplo: 8.1.0                                                                           |
| ZABBIX_VERSION      | Versión de contenedor de Zabbix. Ejemplo: 6.4.10-alpine                                                                  |

Se adjunta un archivo de variables (stack.env) para utilizarlo como ejemplo de uso

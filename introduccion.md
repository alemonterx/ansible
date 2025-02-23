# INTRODUCCIÓN

El módulo ansible.builtin.iptables es un módulo integrado en Ansible que permite gestionar reglas de firewall en sistemas Linux utilizando iptables.

Con este módulo, puedes agregar, eliminar o modificar reglas en las tablas de iptables para controlar el tráfico de red.

### Características principales:

* Permite gestionar reglas en las tablas filter, nat, mangle, raw y security.
* Soporta reglas para aceptar, rechazar o descartar tráfico (ACCEPT, REJECT, DROP).
* Permite definir reglas con parámetros como protocolo, puertos, direcciones IP de origen y destino, interfaz de red, entre otros.
* Puede asegurar que una regla exista o se elimine según sea necesario.
* Es útil para automatizar configuraciones de firewall y mejorar la seguridad en servidores.

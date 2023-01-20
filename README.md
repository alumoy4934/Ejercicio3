Para acceder a un servidor por ssh a un servidor hay que ejecutar el comando:

ssh usuario@ip

Ej: ssh cmoyano@192.168.1.115

Crear usuario admin --> sudo adduser admin

Quitar permiso de acceso por ssh:

   Editar fichero config ssh --> sudo nano /etc/ssh/sshd_config

   Cambiar el valor de PermitRootLogin de yes a no

   Guardar y reinicar servicio con sudo systemctl restart sshd



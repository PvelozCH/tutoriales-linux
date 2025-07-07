# Tutorial de uso Kali Linux.

### Documentacion.
	man comando --> Muestra el manual de uso de un comando específico.
		ejemplo : man ifconfig
	
### Usuarios y grupos de usuarios.
	sudo adduser 'nombreUsuario' --> Crea un usuario nuevo
	sudo usermod -aG sudo nombreUsuario --> Añade usuario a grupo superUsuario.  

### Mapeo de redes.
	ip a --> Te da tu ip en 2 formatos. 
		1: lo --> ip local, no se conecta a internet.
		2: eth0 o Wlan0 --> ip conectada a internet, sirve para mapeo.
		
	nmap -sn ip/mascara --> Lista de dispositivos conectados en red.
	
	sudo wireshark --> interfaz gráfica que muestra tráfico de la red.

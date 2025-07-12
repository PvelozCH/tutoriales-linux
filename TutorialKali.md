# Tutorial de uso Kali Linux.

### Redes 
	Kali directo : (aún no hay información)
	Kali por máquina virtual : 
		

### Documentacion.
	man comando --> Muestra el manual de uso de un comando específico.
		ejemplo : man ifconfig
	
### Usuarios y grupos de usuarios.
	sudo adduser 'nombreUsuario' --> Crea un usuario nuevo
	sudo usermod -aG sudo nombreUsuario --> Añade usuario a grupo superUsuario.  

### Mapeo de redes.
	ip a--> Te da tu ip en 2 formatos. 
	ifconfig --> Hace lo mismo.
		1: lo --> ip local, no se conecta a internet.
		2: eth0 o Wlan0 --> ip conectada a internet, sirve para mapeo.
		
	nmap -sn ip/mascara --> Lista de dispositivos conectados en red.
	
	sudo wireshark --> interfaz gráfica que muestra tráfico de la red, solamente de MI host, no de todos.
		1. Muestra las interfaces a monitorear
		2. El filtro nos permite elegir una ip o un protocolo, por ejemplo http.
		--- 
		TRÁFICO DE TODOS LOS DISPOSITIVOS DE LA RED 
			(En proceso de investigación).
	

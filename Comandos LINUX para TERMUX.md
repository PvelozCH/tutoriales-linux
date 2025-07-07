# Índice
1. Gestor de paquetes
2. Comenzando con lo básico 
3. Utilización de IA Ollama
4. Creación archivos bash
5. Python numpy
6. Git

### 1. Gestor de paquetes
Instalar paquetes: pkg install ...
Desinstalar paquetes: pkg uninstall ...
Ayuda de pkg: pkg help
Actualizar: pkg update and pkg upgrade 
### 2. Comenzando con lo básico 

termux-setup-storage
Me sirve para que Termux tenga acceso a mis archivos internos.

#### Directorios, archivos y más
Lista de directorio actual: ls
Lista de directorio con elementos ocultos: ls -a
Crear un archivo: touch archivo.tipo
Crear archivo oculto: touch .linux
Crear una carpeta: mkdir nombre
Crear carpeta oculta :mkdir .nombre
Cambiar de dir : cd // cd ..
Mostrar ruta actual: pwd

#### Gestionar los archivos 
Copiar archivo en el mismo directorio :              cp archivo.txt ./nuevoNombre.txt

Copiar carpeta y su contenido dentro en el orden en el que está:
cp -r ejemplo ./nuevoNombre 
rm nombreArchivo

Mover 
mv archivo.txt ruta

### 3. IA Ollama
 1. cd ollama 
 2. ./ollama serve &
 3. ./ollama run llama3.2:3b --verbose
### 4. Creación de archivos Bash
1. nano nombre.sh
	1. Crea un archivo.sh y lo edita directamente.
2. Ctrl x, y, enter.
	1. Guarda el archivo.
3. chmod +x nombre.sh
	1. Le da permisos de ejecución.
4. ./nombre.sh
	1. Lo ejecuta



### 5. Numpy en python.
numpy originalmente no funciona en android ya que faltan cabeceras que no están para este sistema operativo. Para poder usar numpy, al momento de instalar python mejor hacerlo así:

pkg install python-numpy

### 6.Git


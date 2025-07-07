
### Gestor de paquetes

Instalar paquetes --> sudo apt install ...
Actualizar --> sudo apt update && sudo apt upgrade -y

#### Directorios, archivos y más

Lista de directorio actual --> ls
Lista de directorio con elementos ocultos --> ls -a
Crear un archivo --> touch archivo.tipo
Crear archivo oculto --> touch .linux
Crear una carpeta --> mkdir nombre
Crear carpeta oculta -->mkdir .nombre
Cambiar de dir --> cd // cd ..
Mostrar ruta actual --> pwd

#### Gestionar los archivos 

Copiar archivo en el mismo directorio -->  cp archivo.txt ./nuevoNombre.txt
Copiar carpeta y su contenido dentro en el orden en el que está --> cp -r ejemplo ./nuevoNombre 
Borrar archivo --> rm nombreArchivo
Borrar carpeta y todo su contenido --> rm -rf nombreCarpeta 
Mover  --> mv archivo.txt ruta

### 3. IA Ollama

 1. pkg install ollama 
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

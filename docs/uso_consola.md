# Comandos Básicos de Navegación

**Verificar Directorio Actual (pwd):** Este comando muestra la ruta del directorio en el que te encuentras actualmente.
```
pwd
```
**Listar Contenido (ls):** Muestra todos los archivos y carpetas en el directorio actual. Se pueden añadir banderas como:
```
ls
```
**AÑADIENDO A ls:**

*-l: Para una lista detallada con información adicional.*

*-a: Para incluir archivos ocultos.*

**Cambiar de Directorio**
```
cd nombre_del_directorio 
```
Permite navegar a otro directorio especificado.* **Usar**
```
 cd ~ 
 ```
 **te lleva al directorio principal del usuario.**

**Volver al Directorio Anterior (cd ..):** Este comando te permite retroceder un nivel en la jerarquía de directorios.
Comandos para Manipulación de Archivos y Directorios

**Crear un Directorio (mkdir nombre_del_directorio):**
 Crea un nuevo directorio con el nombre especificado.
 ```
 mkdir
 ```
**Crear un Archivo (touch nombre_del_archivo):** Genera un archivo vacío con el nombre indicado.
```
touch
```
**Para ver el contenido de un archivo:** Cat nombre del archivo, para ver el contenido.
```
cat
```
**Para editar un archivo** Vim nombre del archivo, para iniciar el editor.
```
vim
```
**Mover o Renombrar Archivos (mv nombre_origen nombre_destino):** Este comando se utiliza tanto para mover archivos a otra ubicación como para renombrarlos.
```
mv nombre_origen nombre_destino
```
**Buscar Archivos (find . -name "nombre_del_archivo"):** Permite localizar archivos dentro del directorio actual y sus subdirectorios.
```
find . -name "nombre_del_archivo"
```
**Borrar Archivos o Directorios (rm nombre_del_archivo o rm -r nombre_del_directorio):** Elimina archivos o directorios, siendo importante tener cuidado ya que esta acción es irreversible.
```
rm nombre_del_archivo
```
```
rm -r
```


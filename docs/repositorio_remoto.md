 # 1. Registrarse en GitHub
Si aún no tienes una cuenta en GitHub:

**Ve a https://github.com/**
Haz clic en Sign up (Registrarse).
Completa los datos requeridos (nombre de usuario, correo y contraseña).
Confirma tu cuenta mediante el correo de verificación.

## 2. Crear un repositorio en GitHub
Inicia sesión en GitHub.
En la parte superior derecha, haz clic en el icono "+" y selecciona "New repository".
Ingresa un nombre para tu repositorio (por ejemplo: MiProyectoC).
Opcionalmente, puedes agregar una descripción y elegir si el repositorio será público o privado.
(Si lo colocas privado es necesario pagar)
No marques ninguna opción de inicialización (README, .gitignore o licencia).
Haz clic en Create repository.

GitHub te mostrará la URL de tu repositorio, algo como:

https://github.com/tu-usuario/MiProyectoC.git
Copia esta URL, la usarás en el siguiente paso.

### 3. Configurar Git y conectar el repositorio remoto
**Si aún no tienes Git instalado, descárgalo aquí:**
🔗 https://git-scm.com/downloads

*Abre Git Bash en la carpeta de tu proyecto local o crea una nueva:*

bash

```
mkdir MiProyectoC
```
```
cd MiProyectoC
```
```
git init
```

Esto inicializa un nuevo repositorio local.

**Vincular el repositorio remoto con tu proyecto local**
Usa el siguiente comando (sustituye la URL con la de tu repositorio en GitHub):

bash

```
git remote add origin https://github.com/tu-usuario/MiProyectoC.git
```

### 4. Agregar archivos y hacer el primer commit
Crea o copia archivos en la carpeta de tu proyecto.
Añade los archivos al área de preparación (staging area):

bash

```
git add .
```
Realiza el primer commit con un mensaje descriptivo:

bash
```
git commit -m "Primer commit: Agregando archivos iniciales"
``` 

#### 5. Subir el proyecto a GitHub (git push)
Sube tu código al repositorio remoto con:

bash


```
git push -u origin main
```

**Git te pedirá autenticación. Ingresa tu usuario y contraseña de GitHub o usa un token de acceso si tienes activada la autenticación de dos factores.**

#### 6. Verificar en GitHub

Ve a tu repositorio en GitHub (https://github.com/tu-usuario/MiProyectoC).
Deberías ver tus archivos ya subidos.

#### 7. Añadir más cambios en el futuro
Cada vez que hagas cambios en tu código, repite estos comandos:

bash

```
git add 
```
```
git commit -m "Descripción de los cambios"
```
```
git push 
```

# GIT IGNORE
 **¿Para qué sirve un archivo .gitignore en un proyecto de C usando Git Bash?**
Cuando trabajo en un proyecto de programación en C, utilizo un archivo .gitignore para decirle a Git qué archivos o carpetas no quiero que rastree ni suba al repositorio. Esto es muy útil por varias razones:

- Evitar Archivos Innecesarios: En mis proyectos de C, a menudo genero archivos temporales, archivos de compilación (como los archivos .o o ejecutables) y otros archivos que no son relevantes para el código fuente. Con el archivo .gitignore, puedo excluir estos archivos automáticamente.

- Mantener el Repositorio Limpio: Al no incluir archivos innecesarios, mi repositorio se mantiene organizado y fácil de manejar. Esto es especialmente importante cuando colaboro con otros, ya que solo compartimos los archivos que realmente importan.

- Proteger Información Sensible: Si tengo archivos de configuración o datos sensibles que no deberían compartirse (como credenciales), los incluyo en el .gitignore para asegurarme de que no se suban accidentalmente.






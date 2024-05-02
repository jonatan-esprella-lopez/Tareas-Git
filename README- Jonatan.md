# **APUNTES DE GIT**
# Primera clase
## ¿Que es un repositorio?
Es un proyecto de GIT.

## git init:
Inicializar Git en un directorio.

## git add [Aqui se puede ingresar los archivos a confirmar], "." para subir todo:
Es el comando usado para realizar la confirmación de los archivos que se guardaran en una versión

## Comandos Git
## git commit
Registra un cambio en el repositorio con un mensaje descriptivo.

## git commit <archivo>
## git commit -m "<descripción>"
## git commit <archivo> -m "<descripción>"
## git log
Muestra el historial de cambios en el repositorio.

## git log --oneline: Muestra los cambios de forma resumida.
## git log --graph: Visualiza el historial de manera gráfica.
README
El README es esencial para presentar un proyecto, generalmente escrito en Markdown. Aquí tienes un Tutorial Markdown.

## Segunda Clase
## git branch
Gestiona las ramas del repositorio.

## git branch: Lista todas las ramas.
## git branch nombreRama: Crea una nueva rama.
## git checkout
Navega entre las ramas del proyecto.

## git checkout nombreRama: Cambia a la rama especificada.
## git merge
Combina los cambios de una rama en otra.

## git merge nombreRama: Fusiona los cambios de la rama especificada.
## git config
Configura la información de usuario en Git.

## git config --global user.name "<nombreUsuario>"
## git config --global user.email "<email>"
Explorador de archivos y ramas
Los archivos se muestran según la rama actual, facilitando la gestión de cambios.

## Conflictos
Git puede enfrentar conflictos al fusionar ramas con cambios en los mismos archivos.
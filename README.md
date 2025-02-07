# **APUNTES DE GIT**
# Primera clase

![IMG 1](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQy8Mk7o0LuR8ZbIc040aZSB7Acnn0zYDY-A5tdcwyUMQ&s)  
## ¿Que es un repositorio?
Es un proyecto de GIT, en el que una persona o varias forman parte.

## **GIT INIT**
Inicializa Git en un directorio.

## **GIT ADD** [Aqui se puede ingresar los archivos a confirmar], "." para subir todo
![IMG 2](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ49ae1yOIdmmo1WlNx8Xpkxwwgcfnfcg_6jw&s)  
Es el comando usado para realizar la confirmación de los archivos que se guardaran en una versión

## **GIT COMMIT**
Registra un cambio en el repositorio con un mensaje descriptivo.
### git commit "<archivo>"
### git commit -m "<descripción>"
### git commit "<archivo>" -m "<descripción>"



## **GIT LOG**
Muestra el historial de cambios en el repositorio con detalles como el **autor** y la **fecha**.
![IMG 3](https://salferrarello.com/wp-content/uploads/2016/10/default-git-log-output.jpg)  

**git log --oneline: Muestra los cambios de forma resumida.**

**git log --graph: Visualiza el historial de manera gráfica.**


# Segunda Clase
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

# Tercera Clase
## **¿Como funcionan las ramas?**

Las ramas dentro de git Hub se dividen en 2

**Rama Principal:** El nombre mas común que tienen es la de **MAIN** aunque depende del proyecto.
**Ramas Segundarisa:** Estas son ramas que parten de la principal, ayudan para realizar cambios sin alterar a la principal.

![ImagenRamas](https://miro.medium.com/v2/resize:fit:801/1*DhagidpZutkaCmAZobmzDQ.png)

## **¿Como se usa el Fast forward?**

**Con Fast forward:** Fusiona una rama A en una rama B de manera directa, integrando los commits de A en B.
**Sin Fast forward:** Fusiona una rama A en una rama B, pero mantiene la visualización separada de A y B en el historial del repositorio.

![FF-NOFF](https://ariya.io/images/2013/09/merging.png)

## **GIT MERGE**
![Merge](https://media.dev.to/cdn-cgi/image/width=800%2Cheight=%2Cfit=scale-down%2Cgravity=auto%2Cformat=auto/https%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fuploads%2Farticles%2Fs3r0ccidrql9drcy2xxj.png)


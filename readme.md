# PASOS A REALIZAR PARA EL EJERCICIO 2
---
## 1. Creamos el repositorio directamente desde GitHub
## ![alt text](./img1.png)
## ![alt text](./img2.png)
---
## 2. Nos situamos sobre el directorio donde queremos poner nuestro repositorio.
---
##  3. Y hacemos un  
``` 
git clone https://github.com/Canales4/repo01
```
---
## 4. Añadimos el fichero con touch readme.md y trabajamos sobre el.
---
## 5. Y despues ejecutamos los siguiente commandos
``` 
git add .

git commit -m "primer commit"

git push 
```

# RESUMEN COMANDOS DE GIT APRENDIDOS

## Recogida de los comandos de git aprendidos

```
git init                    //Para iniciar el repositorio
git add .                   //Para pasar los cambios al staging area
git commit -m "comentario"  //Para commitear y preparar los cambios para la subida
git push                    //Para subir los commits hacia el remoto
git status                  //Para saber el estado del repositorio
git pull                    //Para recoger los cambios realizados en remoto
git rm                      //Para borrar los cambios realizados
git clone <repo>            //Para clonar un repositorio ya creado.
git branch                  //Para listar crear o borrar ramas
git remote add origin url   //Para subir el proyecto por primera vez al repositorio
git help                    //Para ver los comandos existentes de git

//Comandos para la primera configuración

git config --global user.name "nombre"  //Añadir el nombre
git config --global user.email "email"  //ñadir el correo

```
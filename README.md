# SGD-UPES
**Sistema de Gestion Documental - Proyecto de Grado Obtencion de Ing. Ciencias de la Computacion**

# Comando utilizados para gestion de pruebas

---
(Enlace Descarga)[https://sourceforge.net/projects/osboxes/files/v/vb/31-Lx-M-t/21.3/XFCE/64bit.7z/download]

>Username: osboxes
>Password: osboxes.org


---

***Al fnalizar el montaje de la maquina en VirutalBox seguir los siguientes pasos.***

## Comandos Linux Utilizados 
### Preparando  Entonrono
- sudo apt update 
- sudo apt upgrade -y
- sudo apt install docker.io
- sudo docker pull rethinkdb
- sudo docker run -d --name rt --network host rethinkdb
- sudo apt install python3-pip
- sudo apt install python3-venv
- mkdir -p proyecto; cd proyecto ; python3 -m venv app
-  cd app/ ; source bin/activate
-  pip install Flask rethinkdb
  



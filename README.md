PARA ESTA PRACTICA HEMOS APRENDIDO A UNSAR UN REPOSITORIO USAR RAMAS Y  NOS HA AYUDADO A APRENDER COMO FUNCIONA EL GITHUB Y TAMBIEN HACER COMMITS.
## Problemas y dudas
NO SABIA COMO SALIR DE UNA CARPETA EN LA TERMINAL Y TABIEN COMO ABIR LA TERMINAL. durante la practica se me iban olvidando algunos comandoos como es el de cambiar de rama, merge, etc. 


## Historial de la práctica
01f7687 (HEAD -> main) Crear estructura inicial del proyecto
f17a6be (HEAD -> feature/contacto) Añadir página de contacto
01f7687 (origin/main, main) Crear estructura inicial del proyecto
77ffec2 (HEAD -> main, origin/main, origin/HEAD) imagen logo
f17a6be (origin/feature/contacto, feature/contacto) Añadir páginade contacto
01f7687 Crear estructura inicial del proyecto
pablo@MacBook-Air-de-Pablo contacto % git switch feature/contacto
M       README.md
Switched to branch 'feature/contacto'
Your branch is up to date with 'origin/feature/contacto'.
pablo@MacBook-Air-de-Pablo contacto % git log --oneline
f17a6be (HEAD -> feature/contacto, origin/feature/contacto) Añadir página de contacto
01f7687 Crear estructura inicial del proyecto
pablo@MacBook-Air-de-Pablo contacto % git merge main
Updating f17a6be..77ffec2
Fast-forward
 nexfrago-logo-perfil.jpg | Bin 0 -> 54240 bytes
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 nexfrago-logo-perfil.jpg
pablo@MacBook-Air-de-Pablo contacto % git log --oneline
77ffec2 (HEAD -> feature/contacto, origin/main, origin/HEAD, main) imagen logo
f17a6be (origin/feature/contacto) Añadir página de contacto
01f7687 Crear estructura inicial del proyecto
pablo@MacBook-Air-de-Pablo contacto % 
## Observaciones: fetch me ha quedado claro que sirve para actualizar el repositorio, pero no para hacer un pull request, para eso se usa el comando pull request las ramas sirven para trabajar en paralelo comits para indicar las modificaciones merge para fusionar las ramas push para subir los cambios a la rama principal
pull para descargar cambio 
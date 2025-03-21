# Comandos útiles de Git

1. ```git init``` Inicializa un nuevo repositorio de Git en el directorio actual.
2. ```git add .``` Agrega todos los archivos modificados y nuevos al área de preparación.
3. ```git reset .``` Quita los archivos del área de preparación sin eliminar los cambios en el código.
4. ```git commit``` Guarda los cambios en el historial del repositorio, solicitando un mensaje descriptivo.
5. ```git checkout -- .``` Revierte los cambios no confirmados en los archivos del directorio de trabajo.
6. ```git log``` Muestra el historial de commits del repositorio.
7. ```git commit --amend``` Modifica el último commit, permitiendo cambiar el mensaje o agregar nuevos cambios.
8. ```git checkout -b rama-heroes``` Crea y cambia a una nueva rama llamada ```rama-heroes```.
9. ```git checkout master``` Cambia a la rama principal ```master```.
10. ```git branch -d rama-heroes``` Elimina la rama ```rama-heroes``` si no tiene cambios pendientes.
11. ```git push``` Envía los commits locales al repositorio remoto.
12. ```git commit -am``` Agrega y confirma los cambios en un solo paso (solo para archivos ya versionados).
Desarrolle la actividad en bash y en Cmader. Sin embargo, los siguientes pasos son la secuencia en Cmader.

///////////////////////////////////////////////////////
///                                                 ///
///                   S2-Git                        ///
///                                                 ///
///////////////////////////////////////////////////////


Comandos

1.Abrir la consola e imprimir la ubicación actual.----> pwd.
2.Crear una carpeta llamada ejercicios desde la consola----> mkdir ejercicios
3.Cambiar la ubicación a la nueva carpeta que crearon.----> cd ejercicios
4.Abrir la carpeta con VSCode.(ubicados en la carpeta ejercicios)----> code .
5.En VSCode crear una carpeta ejercicio1.----> directamente desde VSC se realiza la creación de la carpeta.
6.Crear un archivo llamado README.md (vacío) dentro de la carpeta ejercicio1.----> directamente desde VSC se realiza la creación del archivo README.md
7.Configurar nombre e email globalmente en git.----> git config --global user.name="German G" // Para el correo git config --global user.email="german95guerrero@hotmail.com"
8.Inicializar el repositorio de git desde la línea de comandos desde la carpeta ejercicios.----> 1. primer paso git init 2. git add .
9.Crear un primer commit con el mensaje “Versión Inicial”. ----> git commit -m "Version inicial".
10.Agregar al README.md los comandos que ejecutaron en cada paso.----> Agregué los presentes comando.
11.Crear un nuevo commit con el mensaje “Agrega solución primer ejercicio”----> Agregados los paso, se hace de nuevo un git add . y un  git commit -m IMPORTANTE se puede abreviar esto con git commit -am "Agregar solución primer ejercicio"
12.Publicar a Github en un repositorio llamado aspirantes-mir-ejercicio-1.---> 1. Crear la llave SSH  ssh-keygen -t rsa -b 4096 -C "german95guerrero@hotmail.com". 2. Agregar la llave "$(ssh-agent -s)"
3. Agregar la cuenta a github. 4. git remote add origin git@github.com:GermanGuerrero95/aspirantes-mir-ejercicio-1.git 5.git branch -M main. 6.git push -u origin main.



13.Enviar el link del repositorio en Github a esta misión.----> Link enviado.
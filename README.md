# CVDS
# Participantes
- Camilo Andres Fernandez Diaz
- Roger Alexander Abril Rodriguez
# Introducion a git - Parte I
1. Abrimos bash y creamos una carpeta para empezar con el proyecto
![image](https://github.com/CamiloFdez/Cvds_lab1/blob/master/assets/Crear%20carpeta.png)
2. Una vez creada la carpeta con el comando init inicializamos el proyecto que queremos crear
![image](https://github.com/CamiloFdez/Cvds_lab1/blob/master/assets/init.png)
3. Añadimos el README.md con el comando Touch README.md y lo añadimos al repositorio, una vez hecho esto usaremos el comando git status para mirar el estado del repositorio y como se podra ver estara creado pero no guardado en github el README y para añadirlo y guardarlo se utilizara el comando git add . que esto permite guardar todos los archivos creados o modificados en el proceso, ya por ultimo se utilizara el git push origin master para soltar todos esos archivos modificados al github y guardar todo en el repositorio creado.
![image](https://github.com/CamiloFdez/Cvds_lab1/blob/master/assets/Readme.png)
4. Ahora enlazaremos la cuenta de nuestro correo institucional dandole click a nuestro usuario y ir a configuracion, en ese apartado encontraremos en el lateral izquierdo un menu y buscaremos email que esta en acceso, una vez seleccionado se añadira el correo que quiera en este caso se usara el de la universidad y se veria tal que asi
![image](https://github.com/CamiloFdez/Cvds_lab1/blob/master/assets/Correo%20enlazado.PNG)
5. Una vez creado el repositorio en blanco en github, se configuro el repositorio local con el repositorio remoto con una serie de comandos que son los siguientes:
    ```bash
      git init // Esto ya hecho al inicializar el proyecto
    ```

    ```bash
      git add . // Añadir todos los archivos
    ```

    ```bash
      git commit -m "Mi primer commit" // Guardar los archivos y cambios con un mensaje
    ```

    ```bash
      git remote add origin https://github.com/Camilofdez/Cvds_lab1.git // Conectar el repositorio remoto con el local
    ```

    ```bash
      git push -u origin master // Subir los cambios, archivos y/o carpetas al repositorio de github creado
    ```  

6. Ya con todo esto quedaria creado el repositorio y este se veria de esta manera:
![image](https://github.com/CamiloFdez/Cvds_lab1/blob/master/assets/Githubfinal.PNG)

# Parte II

1. Se escojieron los roles 
    - Owner : Camilo Fernandez
    - Colaborador : Roger Rodriguez

2. El owner agraga al colaborador 


3. El colaborador acepta la invitacion

4. El colaborador acepta la invitacion

1. Añado a el colaboradpr

2. añado  

# Respuestas
- Parte I: 
    * ¿Para qué sirve y como se usan estos comandos git add y git commit -m “mensaje”?
        - Git add: Este comando de git sirve para mover los cambios que se realizaron en el directorio del trabajo al área del entorno de ensayo, tambien al utilizar este comando se puede empezar a rastrear archivos nuevos, preparar archivos, y hacer otras cosas como marcar archivos en conflicto por combinación.
        - Git commit -m "mensaje": Este comando confirma la instantánea preparada en el historial del proyecto, es decir, una vez al usar el anterior comando y añadir todos los archivos que se quieran añadir al repositorio este comando permite confirmar los cambios y adicional a esto añadir un mensaje de que se hizo para asi servir de guía del paso a paso o de lo que se este haciendo y subiendo mediante el proceso.     

 



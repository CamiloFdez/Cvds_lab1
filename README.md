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

2. El owner agregara al colaborador, para realizar este paso lo primero que se debe hacer es buscar en el repositorio de github el apartado de ajustes, una vez dentro buscaremos colaboradores y dentro de este apartado ingresaremos el correo del colaborador o colaboradores que se quieran agregar al proyecto en este caso sera Roger y a el le llegara un correo para poder participar dentro del repositorio y ua vez aceptado se vera tal que asi:
![image](https://github.com/CamiloFdez/Cvds_lab1/blob/master/assets/Colaboradores.PNG)
- El colaborador le llega la invitacion:
![image](https://github.com/CamiloFdez/Cvds_lab1/blob/master/assets/Invitacion.png)
- El colaborador acepta la invitacion:
![image](https://github.com/CamiloFdez/Cvds_lab1/blob/master/assets/SuccessInvitation.png)

3. Ahora el owner y el colaborador modificaran el README y se subira al mismo tiempo, al momento de hacer esto el primero que detecte que lo haya subido se subira normalmente los cambios pero al otro le generara un error como se vera acontinuación:

![image](https://github.com/CamiloFdez/Cvds_lab1/blob/master/assets/Error.png)  

4. Para resolver estos tipos de problemas primero la persona que le solto el error abrira el IDLE de su preferencia o IntelliJ en este caso se uso Visual Studio Code, usamos start README.md ya que este es el archivo que nos genera el conflicto o simplemente buscamos desde consola nuestra carpeta donde tenemos guardado el proyecto y lo abrimos y quedaria de tal manera:

![image](https://github.com/CamiloFdez/Cvds_lab1/blob/master/assets/ErrorVisual.png) 

Como se podra ver al abrir el archivo se veran las modificaciones hechas por los 2 y el conflicto que hay, para solucionar este problema podemos borrar la parte que no nos interese ya sea del owner o del colaborador, o tambien podemos mezclar dichas partes. En este caso uniremos las partes pero antes de ello debemos borrar estos caracteres para que funcione <<< === y >>> ya que esto señala los archivos que entran en conflicto al hacer pull y quedaria de esta manera:

![image](https://github.com/CamiloFdez/Cvds_lab1/blob/master/assets/CorreccionErrores.png)

Una vez hecho los cambios el IDLE nos mostrara que cambiamos, que borramos o que hicimos para corregir los errores dentro del codigo, como se podra ver en el ejemplo mostrara la version del owner y del colaborador y abajo como se corregio el error que en este caso fue fusionando los 2 cambios hechos por cada uno:

![image](https://github.com/CamiloFdez/Cvds_lab1/blob/master/assets/MuestraCambios.png)

5. Una vez hecho los cambios y corrigiendo los errores le daremos a git status para ver el estado del archivo que entraba en onflicto y se vera de esta manera:

![image](https://github.com/CamiloFdez/Cvds_lab1/blob/master/assets/Archivomodif.png)

Ya para finalizar subiremos este nuevo archivo con las modificaciones de manera normal, usando add, commit y pull o push para subirlo al repositorio y antes de darle en este ultimo comando le daremos a git status una vez mas para asegurar que no hayan errores y que si haya funcionado el comando add:

![image](https://github.com/CamiloFdez/Cvds_lab1/blob/master/assets/ArchivoListo.png)

Y ya con esto solucionamos el problema y podremos trabajar normalmente en el repositorio creado.

# Parte III
1. Cada uno crea una rama :

![image](https://github.com/CamiloFdez/Cvds_lab1/blob/master/assets/crear_rama.png)

![image](https://github.com/CamiloFdez/Cvds_lab1/blob/master/assets/feature_camilo.png)

![image](https://github.com/CamiloFdez/Cvds_lab1/blob/master/assets/feature_roger.png)

2. cada persona hace cambios y realiza el pull request a la rama main/master

![image](https://github.com/CamiloFdez/Cvds_lab1/blob/master/assets/pull.png)

![image](https://github.com/CamiloFdez/Cvds_lab1/blob/master/assets/pull2.png)

3. Se eliminan las ramas:

![image](https://github.com/CamiloFdez/Cvds_lab1/blob/master/assets/borrar_r1.png)

![image](https://github.com/CamiloFdez/Cvds_lab1/blob/master/assets/borrar_r2.png)

Aprobacion del pull request

![image](https://github.com/CamiloFdez/Cvds_lab1/blob/master/assets/apr_2.png)


# Respuestas
- Parte I: 
    * ¿Para qué sirve y como se usan estos comandos git add y git commit -m “mensaje”?
        - Git add: Este comando de git sirve para mover los cambios que se realizaron en el directorio del trabajo al área del entorno de ensayo, tambien al utilizar este comando se puede empezar a rastrear archivos nuevos, preparar archivos, y hacer otras cosas como marcar archivos en conflicto por combinación.
        - Git commit -m "mensaje": Este comando confirma la instantánea preparada en el historial del proyecto, es decir, una vez al usar el anterior comando y añadir todos los archivos que se quieran añadir al repositorio este comando permite confirmar los cambios y adicional a esto añadir un mensaje de que se hizo para asi servir de guía del paso a paso o de lo que se este haciendo y subiendo mediante el proceso.   
- Parte II:
    * ¿Que sucedió al momento de que los dos editaran el README.md al mismo tiempo?
        - Al momento de modificar los dos poniendo cualquier cosa en el README y intentar subir los cambios al mismo tiempo a uno le subira correctamente los cambios al repositorio, pero al otro no le subira y sucedera un error en ese caso debido a que como guardo los datos del repositorio del primero que lo subio, este no tiene dichos cambios y generara asi un error de actualizacion al momento de subirlo, una solucion como se vera en el apartado de la parte 2 es hacer un merge o abrir IntelliJ, Visual Studio Code o el de su preferencia para corregir, eliminar o unir estos cambios propuestos por los 2 usuarios y asi arreglar el error.
- Parte III:
    * ¿Hay una mejor forma de trabajar con git para no tener conflictos? 
        - Si, hay mejores formas para trabajar y no tener conflictos, una de ellas pueden ser las ramas que estas sirven cuando los usuarios estan interactuando con varios archivos pues crean estas ramas para que las modificaciones que cada uno hace queden dentro del repositorio y ya cuando se terminen todos los cambios el usuario hace un Pull Request para que dichos cambios sean aceptados al final o cuando terminen cada cambio realizado para subirlo al repositorio.
    * ¿Qué es y como funciona el Pull Request?
        - Un pull request es una peticion que un usuario le hace al otro para que este último incorpore los commits que están en el repositorio, al crear estas ramas tambien ayudan para fusionar los cambios hechos por los usuarios despues de utilizar este comando, permitiendo asi que os demas revisen dichos cambios y puedan determinar si aprueban o no dichos cambios para solicionar conflictos y errores.

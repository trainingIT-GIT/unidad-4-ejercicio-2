# unidad-4-ejercicio-2

En el siguiente ejercicio vamos a usar código _Java_, pero no hace falta saber programar _Java_. 
Como lo que nos interesa es provocar modificaciones en el contenido de los archivos, el código no tiene por qué estar correcto ni por qué funcionar, y tampoco hace falta entenderlo.

1. Clona en tu máquina, con el comando git clone, el repositorio que hay aquí: 
aquí en **GitHub** 
[https://github.com/trainingIT-GIT/unidad-4-ejercicio-2](https://github.com/trainingIT-GIT/unidad-4-ejercicio-2)
o si lo prefieres en **BitBucket**
[https://bitbucket.org/curso-git-avanzado/unidad-4-ejercicio-2/src/master/](https://bitbucket.org/curso-git-avanzado/unidad-4-ejercicio-2/src/master/)

>Ambos servidores te permiten clonar y acceder a la URL real de _git_:
>- En bitBucket es recomendable copiar la URL asegurándote antes de que estás logueado con tu cuenta. Puedes comprobarlo viendo si en la URL del repositorio aparece tu nombre de usuario.
>- El comando `git clone` te creará una subcarpeta, a menos que añadas un punto; recuerda entrar en ella para empezar a trabajar.

2. De cara a empezar tú un repositorio desde cero, borra la carpeta `.git` para desvincular de este repositorio al proyecto.
3. Inicializa un repositorio local. 
4. Añade al stage todos los archivos y crea un _commit_ inicial con todos ellos.
5. Abre el archivo `lampara/lampara.java` y añade esta nueva propiedad a la clase y guarda el archivo.
 ```java
 private boolean tieneBombilla;
 ```
6. Abre el archivo `lavadora/lavadora.java` y haz que el método `lava()` sea privado. Guarda el archivo.
```java
 private void lava() {
 …
 } 
 ```
7. Añade los cambios al _stage_ y haz un _commit_ con ellos.
8. Abre el archivo `lavadora/lavadora.java` y corrige la visibilidad del método `lava(), hazlo` público. Guarda el archivo.
 ```java
 public void lava() {
 …
 }
 ```
9. Abre el archivo `lampara/lampara.java` y añade este nuevo método. Guarda el archivo.
```java
 public void switch() {
 estaEncendida = !estaEncendida;
 }
 ```
 

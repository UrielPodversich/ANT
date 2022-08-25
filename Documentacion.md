Como realize el ejercicio de git:
cree una carpeta para poder tener en ella todos los archivos de el ejercicio llamada EjercicioGit


Luego cree dentro de ella un repositorio con el comando: (git init).
![img.png](Imagenes/img.png)

Despues cree 2 archivos uno es el Readme.md y el otro es CV.md, el cual le coloque todos datos
falsos excepto por el nombre y el apellido. 
![img2.png](Imagenes/img2.jpg)


Luego, en el archivo Readme.md puse un link que va a llevar directo a el CV.md, para ello 
coloque (parentesis) , la ruta en donde se encuentra el archivo y el nombre del archivo que
quiero linkear. Del lado izquierdo puse [corchetes]y el mensaje que yo quisiera que tuviera. 
Ejemplo:
![img3.png](Imagenes/img3.jpg)

Cree un repositorio en GitHub llamado EjerciciosGit.

![img5.png](Imagenes/img5.jpg)

Una vez que termine de crear los archivos, "linkear" los mismos y crear el repositorio GitHub, escribi en la terminal:<br/>
git branch (nombre) (permite crear, enumerar y eliminar ramas, así como cambiar su nombre). <br/>                             
git remote add origin (link del repositorio)(permite crear, ver y eliminar conexiones con otros repositorios). <br/>          
git add . (añade un cambio del directorio de trabajo, con el . añado todos los archivos/directorios). <br/>                
git commit -m " " (sacas "screenshot" de los cambios que hubo en ese momento del proyecto y agregas un mensaje descriptivo). <br/>
<br /> git push (carga contenido del repositorio local a un repositorio remoto)<br/>                                                
![img4.png](Imagenes/img4.jpg)

Cree otra rama a la cual la llame local. Para eso use el comando: <br/>
git branch local <br/>
Para luego posicionarme sobre la rama local use el comando:<br/> 
git checkout local (El comando git checkout te permite desplazarte entre las ramas creadas por git branch).
![img6.2.png](Imagenes/img6.2.jpg)

Estando posicionado en la rama local agrego los archivos con "git add ." luego creo el/los commit correspondientes y
subo los cambios al repositorio GitHub -EjercicioGit-.

![img7.png](Imagenes/img7.jpg)

![img8.png](Imagenes/img8.jpg)

Una vez subido la rama local al Github, voy al repositorio GitHub -EjercicioGit, clickee el boton de compare & pull request.

![img9.png](Imagenes/img9.jpg)

Creo el pull request.

![img10.png](Imagenes/img10.jpg)

Una vez que se confirma que no hay conflictos con la rama, clickeo el boton de merge pull request.

![img11.png](Imagenes/img11.jpg)

Confirmo el merge.

![img12.png](Imagenes/img12.jpg)

El pull request salio bien, por lo tanto aparecio el siguiente mensaje.

![img13.png](Imagenes/img13.jpg)

Como los cambios se hicieron en el repositorio GitHub, me cambio a la rama main con "git checkout main" y luego hago un pull
con el comando:<br/>
git pull origin main (El comando git pull se emplea para extraer y descargar contenido desde un repositorio remoto y actualizar al instante el repositorio local para reflejar ese contenido.)

![img14.png](Imagenes/img14.jpg)

Lo que hice a continuacion fue clonar el repositorio en otro directorio.
![img_15.png](Imagenes/img_15.jpg)

Luego en el clon modifique el mail para intentar que exista un conflicto a la hora de mergear.

Original:
![img_16.png](Imagenes/img_16.jpg)

Clone:
![img_17.png](Imagenes/img_17.jpg)

Después, agrego el archivo modificado con "git add ." y creo el commit correspondiente.
![img_18.png](Imagenes/img_18.jpg)

Intento pusher pero termina saliendo un error. 
![img_19.png](Imagenes/img_19.jpg)

Hago un pull e intento mergear, sale un error que dice que se encuentra un conflicto y por eso no puede ser mergeado.
![img_20.png](Imagenes/img_20.jpg)

Resuelvo el codigo que contiene el conflicto. Luego agrego todos los archivos modificados y creo los commit correspondientes.
![Img_21.png](Imagenes/Img_21.jpg)

Cree un archivo que se llama Versiones.md en el cual contiene la explicacion de las versiones LOCAL, BASE, REMOTE.
![Img_22.png](Imagenes/Img_22.jpg)

Se pusheo todo lo realizado hasta ahora.



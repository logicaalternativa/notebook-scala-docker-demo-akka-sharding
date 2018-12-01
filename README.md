
 - English  
 - Español

---
 
# English


## Demo akka sharding using notebook jupiter

Repo Notebook de jupyter repo that was used in
[demo de akka sharding](http://www.logicaalternativa.com/slides/akka-sharding) 
This talk was given in **Commit Conf** in November **2018**.

### Requirement

It is needed Docker

### Run the image

Execute the script `jupyter-scala.sh`

    sh jupyter-scala.sh

You can get a message like this

    Copy/paste this URL into your browser when you connect for the first time,
    to login with a token:
        http://localhost:8888/?token=30adbcb834a2a1ae7942825b185b7fe1bcf95d2d01c7b1b9
        
Follow the instructions :-D

### Run javascript demo

You can run the tool that shows the cluster state with 
`runDemoJs.sh` script. 

It just run a simple http server in the directory `js` in the port 80.
It is used `SimpleHTTPServer` python by feel free if you want to use 
another tool.

Run de server javascript demo:

    sh runDemoJs.sh
    

It is necessary run the notebook `others/DataMembers.ipynb` in order 
that the demo works fine.

### How it works?

The main notebook is `2. Ejemplo de cluster.ipynb`. It is 
self-explanatory.
 
You will run the notebook `Apendice. Api rest akka management.ipynb` if
you want to check the state cluster thanks to Akka Management.

Enjoy!.


---

# Spanish

## Demo akka sharding usando notebook jupiter

Repo con los "cuadernos_" de jupyter usados en la 
[demo de akka sharding](http://www.logicaalternativa.com/slides/akka-sharding) 
presentada en el **Commit Conf** en noviembre del **2018**.

### Requistos

Tener docker instalado.

### Arrancar la imagen

Ejecutar el sh `jupyter-scala.sh`

    sh jupyter-scala.sh

Después de arrancar aparece un mensaje en consola parecido al siguiente:

    Copy/paste this URL into your browser when you connect for the first time,
    to login with a token:
        http://localhost:8888/?token=30adbcb834a2a1ae7942825b185b7fe1bcf95d2d01c7b1b9
        
Seguir las instruciones :-D


### Arancar la demo js

La demo que muestra visualmente como está el estado del cluster se puede
arrancar con el script `runDemoJs.sh`. Simplemente arracha un servidor
http en el directorio `js` en el puerto 8001. Para este script se ha 
utilidado el módulo de python `SimpleHTTPServer` pero se puede utilizar
cualquier utilidad similar.

Arrancar servidor para la demo visual del cluster:

    sh runDemoJs.sh
    
Para que la demo funcione hay que ejecutar el notebook de jupyter 
`others/DataMembers.ipynb`

### ¿Cómo funciona?

El cuaderno principal es `2. Ejemplo de cluster.ipynb` el ejemplo es
autoexplicativo.

Para comprobar el estado del cluster con Akka Management se debe 
arrancar el cuaderno `Apendice. Api rest akka management.ipynb`

Espero que lo disfrutes.

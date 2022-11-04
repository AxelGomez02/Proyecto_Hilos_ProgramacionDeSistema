# Proyecto_Hilos_ProgramacionDeSistema
Aqui subiremos nuestros avances en el codigo 
## Diseño de la ventana 
Nuestra ventana consta de unos colores exoticos los cuales pensamos modificalor mas adelante pero ahorita son a modo de prueba  
Donde tenemos 3 elementos basicos que hemos agregado los cuales son Boton de buscar, TextEdit donde ingresamos los las palabras  
Un recuadro de texto donde espermos salga la imagen y descrpcion del texto  

## Expectativa
![Imagen del diseño](https://github.com/AxelGomez02/Proyecto_Hilos_ProgramacionDeSistema/blob/main/Imagenes/Sin%20t%C3%ADtulo.png?raw=true "Esquema de la interfaz")
## Realidad
![ImagenReal](https://github.com/AxelGomez02/Proyecto_Hilos_ProgramacionDeSistema/blob/main/Imagenes/Captura%20de%20pantalla%202022-10-18%20163256.png?raw=true "Interfaz Realizado")
# Introduccion 
## Planteamiento del problema 
En el planteamiento del problema contamos con que nosotros debemos de hacer una interfaz grafica que haga consultas a traves de hilos, los hilos deberan realizar las consultas por medio de palabras clave, y este arrojara el resultado y una imagen con su descripcion  
De los problemas identificados es que necesitamos mostras imagenes con Python y la interfaz grafia diseñada previamente  
Otra dificultas es realizar las consultas y que este nos arroje lo que queremos y despues mostrar la descripcion de las peliculas o pelicula  
# Hilos Parte Teorica 
Un hilo es algo que separa un programa en multiples tareas separadas por lo tanto le da al procesador una mayor flexibilidad en la forma que administran las tareas  
Los hilos es una unidad de instruccion de procesamiento mas pequeña que el sistema operativo le da al procesador  
Utilizar miltiples hilos para correr un solo programa donde tengas que hacer varias repeticiones en una tarea 
hace al programa mas eficiencte pues lleva varias tareas al mismo tiempo  
Los hilos no deben ser confundidos con los nucleos de un procesador  
Los hilos existen a nivel software mientras que los nucleos son procesadores fisicos separados e instalados en un solo chip.
### Hilos en la programacion
#### ¿Como funcionan los hilos en la programacion?
Nos permiten separar tareas complejas en tareas mas simples y concretas, asi si un proceso falla no bloquea todo el programa  
Cabe destacar que un hilo es un flujo de control secuencial por lo que un hilo es similar a un programa secuencial asi que cuenta con un comienzo y un final  
## Operaciones Basicas 
SLEEP(); Duerme el proceso por un tiempo determinado  
Stop(); Detiene el hilo haciendo que los atributos sean publicos   
Start(); Inicia la ejecucion    
Wait(); Pausa la ejecucion     
notify(); Nos devuelve un valor si un hilo esta en funcionamiento  
notifyAll() lo mismo que notify pero para todos los hilos funcionales   

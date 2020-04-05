# Reconocimiento y reconstruccion de mapas de desgaste usando machine learning


<img src="/portada.png" style="width:400px;" class="center">


- Brayan Camilo Valenzuela Rincón


**Universidad Industrial de Santander (UIS)**<br/>
**Ingenieria de Sistemas**<br/>
**2020**<br/>

# Introducción:

Este repositorio fue creado con el objetivo de hacer publico el código realizado como proyecto final de la asignatura: Astronomía planetaria. Este proyecto consistió en implementar un algoritmo el cual, basado en técnicas de visión artificial y patrones de características, permitiera alinear los cuadros en una secuencia de video de timelapse del cielo, según el desplazamiento de las estrellas, dando como resultado un video en el que se puede apreciar el movimiento de rotación de la tierra. 

# Data set:

el video usado como prueba para este proyecto fue tomado de: https://www.youtube.com/watch?v=0ma0SNEAzes

# Modelo y metodos usados:

- Homografia.

- Puntos de caracteristicas ORB

# Uso del algoritmo:

- Para probar le algoritmo realizado con un video propio, debe copiarlo en la misma ruta en la que descargo el proyecto.
- Abrir el notebook: Rotacion.ipynb.
- En la funcion *extraer_fotogramas* cambiar *time_laps3.mp4* por el nombre del nuevo video.
- Por ultimo se ejecuta cada celda del notebook. El video resultado sera guardado en la ruta del proyecto con el nombre de: *matches.mp4*.

# Referencias:

- https://www.learnopencv.com/image-alignment-feature-based-using-opencv-c-python/
- https://gitlab.com/bivl2ab/academico/cursos-uis/cv/cv-uis-student.git

# Mi laboratorio de Terminal y Git
Autor: Julio González Bonilla

## Aprendido
- MatIA: recuento de pinzas con datos sintéticos.
- Ejecución: *saludo.sh* es el ejecutable maestro.
- IA: No he usado inteligencia artificial para esta actividad.

## Comprobación
He probado los casos coincide, faltan y sobran pinzas.

## Comandos y análisis
1) ¿Qué diferencia hay entre *>* y *>>*?

    *>* reemplaza el contenido del archivo, mientras que *>>* añade al final.

2) ¿Qué hace la tubería *|*?

    *|* hace que la salida del primer comando se convierta en la entrada del siguiente.

3) ¿Por qué una tijera no aumenta el contador?

    Porque en el código hemos especificado que el contador solo aumenta cuando la variable *instrumento* es igual a "pinza".

4) ¿Qué indican las tres líneas del informe?

    La primera indica la cantidad de pinzas esperadas en la lista *instrumentos*, la segunda la cantidad observada y la última el resultado de la comparación.

5) ¿Qué diferencia hay entre guardar un archivo, *git add*, *git commit* y *git push*?

    Cuando guardas un archivo este se queda en el almacenamiento local del ordenador.

    *git add* es un comando de Git que permite añadir nuevos archivos (o versiones de los ya existentes) a la carpeta en la que se está trabajando.

    *git commit* confirma los cambios que se hayan hecho con *git add*.

    *git push* actualiza en GitHub la carpeta con las nuevas modificaciones.
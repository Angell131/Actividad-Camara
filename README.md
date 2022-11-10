# Actividad-Camara
kotlin use camera and select screenshot

Realiza las siguientes tareas:
-En la pantalla de inicio, muestra una caja de texto con el título Captura de imagenes.
Añades un textView diciendo 'Captura de imagenes'.
-Añade en esta pantalla también un texto explicando brevemente al usuario ladiferencia entre click y longclick.
Añades otro textView para la explicación.
-Las imágenes se guardarán el carpeta llamada "Imágenes favoritas".
En storage, en Pictures creas la nueva carpeta 
-Las fotos se guardarán con el nombre de archivo foto_XXX.jpg, siendo XXX los milisegundos de la fecha actual.
En la linea 74 le pones el nombre a la foto. O creas una variable y le añades la fecha de los miliseg o lo pones a cholón con + System.currentTimeMillis()
-Indica en Device File explorer dónde físicamente están almacenadas las imágenes.
/storage/self/primary/Pictures/Imagenes_Favoritas

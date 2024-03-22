
# parcial-devops

¡Hola Mundo!, para correr este app en una imagen de docker, sigue estos pasos:

> Primero ubica la terminal en tu proyecto, Luego

ng build

docker build -t parcial-devops-blvargas .

docker images-- Luego copias el id de la imagen creada

docker run -d -p 80:80 --name nombre_deseado nombre_de_la_imagen_o_id_de_la_imagen


abre tu navegador con la ruta:

localhost:80

Recuerda limpiar el caché :D


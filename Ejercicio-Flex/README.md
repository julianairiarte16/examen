# Ejercicio-Flex

Ejercicio básico de Flexbox:

1- Representa la escena acomodando a los personajes en la playa. Recuerda pensar en los contenedores de estos elementos como cajas para poder mover los ítems.
2- Además, ten en cuenta que la imagen de fondo es justamente eso: un background-image.
3- Debe estar posicionado con Flexbox (excluyente).


![alt text](resultado.png)
  
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Imagen con varias imágenes dentro</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <div class="main-image">
            <img src="fondo-flex.jpg" alt="Imagen principal">
            <div class="sub-images">
                <img src="amarillo.png" alt="Imagen 1" class="yellow-sub-img"/> 
                <img src="rojo-corre.png" alt="Imagen 2" class="img red-sub-img"/> 
                <img src="chiquitos.png" alt="Imagen 3"class="img hatchlings-sub-img"/>
                <img src="medita.png" alt="Imagen 4" class="img white-sub-img"/>
                <img src="negro.png" alt="Imagen 5" class="img black-sub-img"/>
            </div>
        </div>
    </div>
</body>
</html>

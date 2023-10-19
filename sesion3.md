<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 


<!-- Su documentación aquí -->

Actividad: Adición de contenido multimedia en un sitio web utilizando etiquetas HTML5
Completa el siguiente código HTML añadiendo el contenido multimedia correspondiente en cada sección:

- 4 Imagenes
- 2 Videos
- 4 Audios
- 2 Inline Frame
Utiliza encabezados para títulos en cada elemento


Crea una descripción para cada elemento utilizando párrafos.

Además, puedes emplear las siguientes etiquetas para mejorar la estructura y estilo de tu contenido:

- Usa "strong" para resaltar texto importante.
- Utiliza "br" para insertar saltos de línea si es necesario.
- Agrega "span" para aplicar estilos específicos a porciones de texto.
- Emplea "i" para enfatizar o dar énfasis a palabras o frases.
- Utiliza "u" para subrayar texto cuando sea necesario.
- Considera el uso de "div" para crear secciones o contenedores para tu contenido, lo que puede facilitar la organización y el diseño de la página.

## Solución: 

Código base:

```
<!DOCTYPE html>
<html>

<head>
    <title>Etiquetas Multimedia HTML5</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #1adae7;
            color: white;
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: blue;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body background="olga-thelavart-vS3idIiYxX0-unsplash.jpg">

    <header>
        <h1>Etiquetas Multimedia HTML5</h1>
        <h3>La forma más fácil de agregar multimedia a tus sitios web</h3>
    </header>

    <section>
        <h2>
            <font color="0DF8F4">Imagenes de muestra</font>
        </h2>
        <h1> </h1>
        <p>A continuacón expondré un conjunto de imágnes en relación a los personajes de la famosa caricatura
            <strong>Escandalosos</strong> la cual fue
            parte de mi infancia y quisiera representar mediante esta página. </p>

        <h1>Imágen de muestra en relación al trío de personajes.</h1>
        <img src="https://i.pinimg.com/originals/10/34/e5/1034e52d87b89d33c01c783cfb319aa4.gif" width="400">
        <h1>Oso Pardo</h1>
        <img src="latest (1000×1071) - Google Chrome 17_08_2023 10_01_35 a. m. (2).png" width="400">
        <h1>Oso Polar</h1>
        <img src="latest (1000×1071) - Google Chrome 17_08_2023 10_01_31 a. m. (2).png" width="400">
        <h1>Oso Panda</h1>
        <img src="latest (1000×1071) - Google Chrome 17_08_2023 10_01_13 a. m. (2).png" width="400">
        <img src="" width="">
        <p>Las imágnes expuestas anteriormente expresan un conjunto de personajes de televisión que hicieron parte de mi
            infancia. Razón por la que busco retratarlos aquí.</p>
    </section>

    <section>
        <h2>
            <font color="0DF8F4">Videos de muestra en relación a los carismáticos y emblemáticos personajes de
                caricatura.</font>
        </h2>
        <h1>Video #1 de muestra.</h1>
        <video src="¡Nuestro canal de YouTube! _ Escandalosos _ Cartoon Network (1).mp4" controls width="800"></video>
        <h1>Video #2 de muestra.</h1>
        <video src="El sueño de Panda _ Escandalosos _ Cartoon Network.mp4" controls width="800"></video>
        <p>Contenido sobre videos...</p>
    </section>

    <section>
        <h2>
            <font color="0DF8F4">Narrativas</font>
        </h2>
        <p>A continuación, adjunto un conjunto de audios dónde se narran breves experiencias del trío de personajes;
            Buscando representar un poco de sus aventuras mediante la imaginación.</p>
        <h1>Narrativa #1</h1>
        <audio src="y2mate.com - OSOS A DIETA  ESCANDALOSOS.mp3" controls></audio>
        <h1>Narrativa #2</h1>
        <audio src="y2mate.com - LA AGONÍA DE LA DIETA  ESCANDALOSOS.mp3" controls></audio>
        <h1>Narrativa #3</h1>
        <audio src="y2mate.com - EL CELULAR DE PANDA  ESCANDALOSOS.mp3" controls></audio>
        <h1>Narrativa #4</h1>
        <audio src="" controls></audio>

    </section>

    <section>
        <h2>
            <font color="0DF8F4">iFrames
        </h2>
        <iframe src="https://www.sensacine.com/series-tv/mejores/" width="900" height="800"></iframe>
        <br><br>
        <hr><br>
        <iframe src="https://www.internetizado.com/paginas-web/donde-ver-series-online-gratis" width="900"
            height="800"></iframe>
    </section>

    <footer>
        Juan Miguel Gómez Carmona
        <br>
        <br>
        CESDE
        <br>
        <br>
        &copy;2023
    </footer>

</body>

</html>`





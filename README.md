# ASIX1_0373_A00_IntroGitHub
## Primer repositorio en ASIX1 del curso 25-26 en la aplicacion
### Es primera toma de contacto con github
#### Soy Martí Pidemunt

<a href="Imagen1">Enlace a imagen</a>
Esto está en __negrita__
Esto está en **negrita**

Esto está en _cursiva_
Esto está en *cursiva*

__*TEXTO*__
**__TEXTO__**

ABRIR ETIQUETA 1
     ABRIR ETIQUETA 2
        contenido
     CERRAR ETIQUETA 2
CERRAR ETIQUETA 1

1. Elemento 
    * Elemento desordenado 1.1
    * Elemento desordenado 1.2
2. Elemento 2
    * Elemento desordenado 2.1
    * Elemento desordenado 2.2
3. Elemento 3
    * Elemento desordenado 3.1
    * Elemento desordenado 3.2

* Elemento desordenado 1
* Elemento desordenado 2
* Elemento desordenado 3

regooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooqejnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnngnernognerneroreverjvernvnervvnerovnerrvnenrvnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnnn 

```html
<p>Esto es un parrafo</p>
```
[link](https://stackoverflow.com/questions/41345160/display-link-url-in-markdown/ "Manual oficial de Markdown")

![alt text](iniesta.png/ "Imagen random de un archivo")

| *Jugador* | Equipo | Nombre |
|------------:|:---------------:|:--------------|
| 32 | Lakers | Magic Jonhson |
| 33 | Celtics | Larry Bird |
| 23 | Bulls | Michael Jordan |


<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Primera pagina</title>
</head>
<body>


    <a href="#imagen1">Enlace a Imagen uno</a>
    <!--Esto es un comentario-->
    <h1>Hola mundo</h1>
    <h2>Mi primera pagina web</h2>
    <h3>Subtitulo</h3>
    <h4>Subsubtitulo</h4>
    <h5>Subsubsubtitulo</h5>
    <h6>Subsubsubsubtitulo</h6>

    <!-- Etiquetas de parrafo -->
    <p>ipsum dolorsit, amet consectetur adipisicing elit. Facere accusamus tempora neque voluptas, alias, eius molestias magni, amet accusantium impedit nesciunt labore quia cupiditate temporibus illum ab blanditiis optio nam.</p>

    <!-- Etiquetas de salto de linea -->
    <br>
    <hr>

    <!-- Etiqueta de destacar y parrafo -->
    <p><em>ipsum dolor</em> sit, amet consectetur adipisicing elit. Facere accusamus tempora neque voluptas, alias, eius molestias magni, amet accusantium impedit nesciunt labore quia cupiditate temporibus illum ab blanditiis optio nam.</p>    
    <p><b>ipsum dolor</b> sit, amet consectetur adipisicing elit. Facere accusamus tempora neque voluptas, alias, eius molestias magni, amet accusantium impedit nesciunt labore quia cupiditate temporibus illum ab blanditiis optio nam.</p>
    <p><strong>ipsum dolor</strong> sit, amet consectetur adipisicing elit. Facere accusamus tempora neque voluptas, alias, eius molestias magni, amet accusantium impedit nesciunt labore quia cupiditate temporibus illum ab blanditiis optio nam.</p>

    <!-- Etiqueta para marcar un trozo de contenido en linea -->
    <p><span>ipsum dolor</span> sit, amet consectetur adipisicing elit. Facere accusamus tempora neque voluptas, alias, eius molestias magni, amet accusantium impedit nesciunt labore quia cupiditate temporibus illum ab blanditiis optio nam.</p>

    <ol>  <!-- Etiqueta para definir una lista ordenada -->
        <li>Primer elemento de la lista</li> <!-- Esto es un elemento, se define con "li" -->
            <ol>
                <li>SubElemento 1.1</li>
                <li>SubElemento 1.2</li>
            </ol>
        <li>Segundo elemento de la lista</li>
        <li>Tercer elemento de la lista</li>
    </ol>

 <ul><!-- Etiqueta para definir una lista desordenada -->
        <li>Primer elemento de la lista</li> <!-- Esto es un elemento, se define con "li" -->
        <li>Segundo elemento de la lista</li>
        <li>Tercer elemento de la lista</li>
    </ul>
    <BR>
    <!-- Etiqueta para insertar imagenes -->
    <img id="imagen1" src="./MULTIMEDIA/IMAGENES/images.jpg" alt="Foto de SOLDIUER BOY" >

    <!-- Etiqueta para insertar enlaces -->
     <br>
     <a href="./VIAJES/NYC/viajes.html">Viaje a NYC</a>


</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>

    <table border="1">
        <thead>
            <tr>
                <th>ORDEN</th>
                <th>ATLETA</th>
                <th>TIEMPO</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1</td>
                <td>Michel Eaton</td>
                <td>2:23:00</td>
            </tr>
            <tr>
                <td rowspan="2">2</td>
                <td colspan="2">Andrea Bocelli</td>

            </tr>
            <tr>

                <td>Steve Carmaikel</td>
                <td>2:50:00</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <td>ORDEN</td>
                <td>ATLETA</td>
                <td>TIEMPO</td>
            </tr>
        </tfoot>
    </table>
    <caption>tabla Clasifcatoria de maraton de BCN</caption>

    <form action="URLdeDestino.html" method="GET">
        <label for="username">Username:</label>
        <input type="text" name="username" id="username" required>
        <br>
        <label for="realname">Nombre real:</label>
        <input type="text" name="realname" id="realname">
        <br>

        <fieldset>
            <legend>Carnet de conducir</legend>
            <label for="carnetsi">SI:</label>
            <input type="radio" name="carnet" value="carnetsi" id="carnetsi">
            <label for="carnetno">NO:</label>
            <input type="radio" name="carnet" value="carnetno" id="carnetno">
        </fieldset>
        <br>
        <fieldset>
            <legend>Gustos musicales</legend>
            <label for="pop">Pop:</label>
            <input type="checkbox" name="musica[]" value="pop" id="pop">
            <label for="heavy">Heavy:</label>
            <input type="checkbox" name="musica[]" value="heavy" id="heavy">
            <label for="pachanga">Pachanga:</label>
            <input type="checkbox" name="musica[]" value="pachanga" id="pachanga">
        </fieldset>
        <br>
    <label for="nacioniladidad">Nacionalidad:</label>
        <select name="Nacionalidad" id="nacioniladidad">
            <option value="españa">España</option>
            <option value="peru">Peru</option>
            <option value="argentina">Argentina</option>
            <option value="chile">Chile</option>
        </select>
        <br>
        <label for="observaciones">Observaciones:</label><br>
        <textarea name="observaciones" id="observaciones" rows="5" cols="30" placeholder="Introduce aqui cualquier observacion que tengas"></textarea>
        <br>
        <button type="submit" name="Enviar" value="enviar">Enviar Datos</button>
    </form>
</body>
</html>

Para subir los cambios al GitHub.
PS C:\Repositorios_Git\ASIX1_0373_A00_IntroGitHub> git init
Reinitialized existing Git repository in C:/Repositorios_Git/ASIX1_0373_A00_IntroGitHub/.git/

PS C:\Repositorios_Git\ASIX1_0373_A00_IntroGitHub> git add .

PS C:\Repositorios_Git\ASIX1_0373_A00_IntroGitHub> git commit -m "Añadidas 2 lines al README"
[main ef1ba7d] Añadidas 2 lines al README
 1 file changed, 2 insertions(+)

PS C:\Repositorios_Git\ASIX1_0373_A00_IntroGitHub> git push origin main
info: please complete authentication in your browser…
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 380 bytes | 27.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/martipidemunt/ASIX1_0373_A00_IntroGitHub.git
   2dfd2b4..ef1ba7d  main -> main


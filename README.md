# AE1a-Mi-documentaci-n-apuntes

## Index:

1. [GITHUB](#Github)
2. [Markdown](#Markdown)
3. [HTML](#HTML)

# Github
Github es una página web donde programadores guardan su código y trabajan juntos en proyectos. Funciona como una "nube" para el código, permitiendo que varios programadores hagan cambios sin borrar el trabajo de otros, ya que guarda todo el historial de cambios. También ayuda a discutir mejoras, revisar el trabajo y organizar tareas, haciendo más fácil crear software en equipo.
## Cracion de repositorio y clonacion con cmd
Para crear un repositorio tenemos que entrar al 'Your repositories' una vez que entremos al repositorio le damos al 'New'.
<br>
![img1](./img/img1.png "img1")

Y nos abrira esta ventana y desde aqui añadimos el nombre de repositorio, añadir descripcion, que sea Public, seleccionamos Add a REAME file y le damos al crear
<br>
![img](./img/img2.png "img2")

Una vez que creamos el repositorio le damos al "Code" y copiamos la URL
<br>
![img](./img/img3.png "img3")

Y en siguiente paso es entrar al cmd y nos vamos al directorio donde guardamos todos los repositories, desde aqui usamos el comando: git clone (URL que hemos copiado antes). Este comando sirve para clonar el repositorio.
<br>
![img](./img/img4.png "img4")

Resultado: aqui podemos ver que ya esta clonado.
<br>
![img](./img/img5.png "img5")
<br>
## Comando basico de git
* **git init**: para iniciar 
* **git branch**: para ver la rama donde trabajamos
* **git branch -M main**: situar el repositorio en main
* **git add .**: para añadir todos los archivos
* **git commit -m "añadir comentario"**: sirve para añadir commit
* **git push origin main**: subir el cambio
* **git remote add origin "link de URL"**: es sincronizar repositorio local con el web
* **git pull**: bajar el cambio
* **git clone**: sirve para clonar
<br>

# Markdown
Markdown es un lenguaje de marcado ligero que se utiliza para formatear texto de manera sencilla y rápida. Fue creado por John Gruber en 2004 con el objetivo de que las personas pudieran escribir de forma legible y fácil de escribir, mientras que al mismo tiempo generaba contenido que pudiera convertirse en HTML (el lenguaje utilizado para las páginas web).

# Comando basico de markdown

Mostracion en markdown: (niveles de encabezado)

```
# Perimer nivel de encabezado
## Segundo nivel de encabezados
### Tercero nivel de encabezados
#### Quarto nivel de encabezados
##### Quinto nivel de encabezados
###### Sexto nivel de encabezados
```
Resultado: 
# Perimer nivel de encabezado
## Segundo nivel de encabezados
### Tercero nivel de encabezados
#### Quarto nivel de encabezados
##### Quinto nivel de encabezados
###### Sexto nivel de encabezados


## Coamdo para poner en negrita y cursiva

Para ponerlo en negrita usamos esto ``** **`` y para cursiva podemos usar ``* *`` o ``_ _``.

Mostracion en markdown:
```
 *0373* del ciclo de **ASIX** o DAW del curso _2425_.
```
Resultado:
 *0373* del ciclo de **ASIX** o DAW del curso _2425_.
 

## Tabla ordenada y desordenada
Mostracion desde markdown: (los ordenada llevan numeros y los desordenadas usan simbolos)
```
1. Primer punto de la lista
    1. Primer elemento de la sublista 1
    2. Segundo elemento de la sublista 1
2. Sgundo punto de la lista
    * Primer elemento de la sublista 1
    * Segundo elemento de la sublista 1
3. Tercer punto de la lista

* Primer punto de lista desordenada
- Segundo punto de lista desordenada
+ Tercer punto de lista desordenada
```
Resultado:
1. Primer punto de la lista
    1. Primer elemento de la sublista 1
    2. Segundo elemento de la sublista 1
2. Sgundo punto de la lista
    * Primer elemento de la sublista 1
    * Segundo elemento de la sublista 1
3. Tercer punto de la lista

* Primer punto de lista desordenada
- Segundo punto de lista desordenada
+ Tercer punto de lista desordenada


**Como mostrar codigo en un repositorio**
usando este simbolo "```" para mostrar los codigos.

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minds of Tomorrow</title>
    <link href="./css/estilos.css" rel="stylesheet" type="text/css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Chakra+Petch:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,500;1,600;1,700&family=Honk:MORF,SHLN@5,66.7&family=Kanit:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Magra:wght@400;700&family=Nunito:ital,wght@0,200..1000;1,200..1000&family=Permanent+Marker&family=Varela+Round&display=swap');
    </style>
```
## Añadir url

- Añadimos un texto o un titulo dentro de corchetes.
- Y luego añadimos url dentro de la parenteci.
```
[textoClicable](URL "Titulo opcional")

[Pagina web de Joan23](https://www.fje.edu/ca/jesuites-bellvitge "Titulo opcional")
```

### Como poner una imagen

```
![TextoAlternativo](UbicacionDeLaImagen "Titulo opcional")

![Messi](messi.jpg "Titulo opcional")
```

### Como poner tabla
Mostracion desde markdown:
```
|Titulo 1 | Titulo 2 | Titulo 3 |
|-----------|:----------:|--------------|
|SMX2 |Curso 2324|25| 
|**ASIX1** |Curso 2425|33| 
|DAW2 |Curso 2425|35| 
```
- Los dos puntos (:) sirven para decidir cómo se alinean las columnas en una tabla (a la izquierda, en el centro o a la derecha).
- No es necesario que las columnas queden perfectamente alineadas en el código; eso es solo para que sea fácil de leer.
- Para hacer una tabla, usa al menos tres guiones (---) para separar los títulos (encabezados) de las columnas del contenido de la tabla.

Resultado:
|Titulo 1 | Titulo 2 | Titulo 3 |
|-----------|:----------:|--------------|
|SMX2 |Curso 2324|25| 
|**ASIX1** |Curso 2425|33| 
|DAW2 |Curso 2425|35| 

# HTML
HTML (HyperText Markup Language) es el lenguaje de marcado utilizado para estructurar y presentar contenido en la web. Define la estructura de una página web mediante etiquetas.
<br>

## Estructura Básica de un Documento HTML
Estructura de html:
```
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Título de la Página</title>
</head>
<body>
    
</body>
</html>
```
## Explicacion: 

- **``<!DOCTYPE html>``:** Define el tipo de documento, en este caso es HTML5.
- **``<html>``:** Etiqueta raíz que contiene todo el contenido de la página.
- **``<head>``:** Contiene metadatos sobre el documento (título, codificación, etc.).
- **``<meta charset="UTF-8">``:** Define la codificación de caracteres, importante para caracteres especiales. 
- **``<title>``:** Título de la página que aparece en la pestaña del navegador.
- **``<body>``:** Contiene el contenido visible de la página (texto, imágenes, enlaces, etc.).

## Etiquetas Básicas de HTML

|Comando | Funcion | 
|-----------|:----------:|
|``<h1>, <h2>, ..., <h6>``|Títulos de diferentes tamaños (h1 es el más grande, h6 el más pequeño).|
|``<p>``|Para texto|
|``<br>``|Salto de línea.|
|``<hr>``|Línea horizontal.|
|``<b> o <strong>``|Texto en negrita|
|``<i> o <em>``|Texto en cursiva.|
|``<u>``|Texto subrayado.|
|``<li>``|Se lleva en cada elemento de la lista|
|``<ul>``|lista desordenada|
|``<ol>``|lista ordenada|
|``<!--comentario-->``|Para añadir comentario|


## Ejemplo de la lista desordenada

Mostracion en html: para crear una lista desordenada tenemos que usar el etiqueta (ul) uno en el pripncipio y una en el finla y en el medio usamos li para listarlo.

Ej:
```
<ul>
    <li>Elemento 1</li>
    <li>Elemento 2</li>
</ul>
```

Resultado:

<ul>
    <li>Elemento 1</li>
    <li>Elemento 2</li>
</ul>

## Ejemplo de la lista ordenada
Para crear una lista desordenada tenemos que usar el etiqueta (ol) uno en el pripncipio y una en el finla y en el medio usamos li para listarlo.

Mostracion en html:
```
<ol>
    <li>Primer elemento</li>
    <li>Segundo elemento</li>
</ol>
```
Resultado:
<ol>
    <li>Primer elemento</li>
    <li>Segundo elemento</li>
</ol>

<br>

## Enlaces
Usamos este comando para crear un enlace: ```<a href="pegar url de un enlace que quieres poner">Texto del enlace</a>```

html:
```
<a href="https://es.wikipedia.org/wiki/Lionel_Messi">Messi</a>
```

Resultado: 

<a href="https://es.wikipedia.org/wiki/Lionel_Messi">Messi</a>

## Imagenes
Usamos este comando para mostrar un imagen: ```<img src="ruta_imagen" alt="descripcion de la imagen">``` en el img src ponemos la ruta de la imagen y en el alt description de la imagen. 

html:
```
<img src="./img/messi.png" alt="imagen messi">
```
Resultado: 
<br>
<img src="./img/messi.png" alt="imagen messi">

## Tabla de contenidos
En HTML que permite a los usuarios navegar entre diferentes secciones de la página de manera rápida.<br>

### Creamos un indice principal:
```
    <h1 id="indice">Indice</h1>
    <a href="#seccion1">Enlace a primer seccion</a><br>
    <a href="#seccion2">Enlace a segundo seccion</a><br>
    <a href="#seccion3">Enlace a tercer seccion</a><br>
```
* En el encabezado ``<h1 id="indice">Indice</h1>`` he crado el titulo 'Indice' y le asignado el identificador id="indice"
* Cada enlace ``<a href="#seccion1">`` Enlace a primer seccion tiene un atributo href que apunta a un id específico (#seccion1, #seccion2, #seccion3), que son los identificadores de cada sección.<br>

### Ruta absoluta:
En HTML es una URL completa que lleva directamente a un recurso especifico, como una paquina web o imagen, sin importat desde donde se acceda.

Ej: 
```
<a href="https://www.ejemplo.com/pagina.html">Ir a página</a>
```

### Ruta relativa:
Una ruta relativa no usa la URL completa en cambio, indica la ubicación de un archivo en relación con la ubicación del archivo actual. Esto es útil para organizar archivos dentro de un proyecto sin preocuparse por el dominio completo o la ubicación específica.

Ej: 
```
<a href="../pagina.html">Ir a página</a>
```

### Secciones de Contenido:
```
    <h4 id="seccion1">Primer seccion</h4>
    <p>Lorem ipsum...</p>
```
* Cada sección comienza con un encabezado ``<h4>`` que tiene un id único (por ejemplo, id="seccion1" para la primera sección). Este identificador coincide con el destino al que apunta el enlace en el índice (href="#seccion1").<br>

### Organizacion de ficheros:
Cuando una aplicación web es grande, tiene muchos tipos de archivos diferentes: páginas HTML, estilos CSS, imágenes, videos, etc. Para mantener todo ordenado y fácil de encontrar, es importante organizarlos en carpetas.

Por ejemplo, podriamos crear una estructura como esta:
```
|--web 
| |--imatges 
| | |--img1.png 
| | |--img2.jpg 
| | |--img3.gif 
| | |... 
| |--videos 
| | |--video1.mpg 
| | |--video2.mpg 
| | |... 
| |--css 
| | |--estil.css 
| | |... 
| |--index.html 
| |--seccion1.html 
| |--seccion2.html 
| |--contacte.html 
| |... 
```

# SEM2c: Contenedores, formularios y tablas















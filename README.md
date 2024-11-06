# AE1a-Mi-documentaci-n-apuntes
Apuntes durante el curso

# Cracion de repositorio y clonacion con cmd
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
* git: para iniciar 
* git branch: para ver la rama donde trabajamos
* git branch -M main: situar el repositorio en main
* git add .: para añadir todos los archivos
* git commit -m "añadir comentario": sirve para añadir commit
* git push origin main: subir el cambio
* git remote add origin "link de URL": es sincronizar repositorio local con el web
* git pull: bajar el cambio
* git clone: sirve para clonar
<br>
## Comando basico de markdown

# Perimer nivel de encabezado
## Segundo nivel de encabezados
### Tercero nivel de encabezados
#### Quarto nivel de encabezados
##### Quinto nivel de encabezados
###### Sexto nivel de encabezados


##Coamdo para poner en negrita y cursiva

```
 *0373* del ciclo de **ASIX** o DAW del curso _2425_.
```
 *0373* del ciclo de **ASIX** o DAW del curso _2425_.
 

## Tabla ordenada y desordenada
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
usando este simbolo "```" 

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
### Añadir url

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

```
|Titulo 1 | Titulo 2 | Titulo 3 |
|-----------|:----------:|--------------|
|SMX2 |Curso 2324|25| 
|**ASIX1** |Curso 2425|33| 
|DAW2 |Curso 2425|35| 
```
|Titulo 1 | Titulo 2 | Titulo 3 |
|-----------|:----------:|--------------|
|SMX2 |Curso 2324|25| 
|**ASIX1** |Curso 2425|33| 
|DAW2 |Curso 2425|35| 

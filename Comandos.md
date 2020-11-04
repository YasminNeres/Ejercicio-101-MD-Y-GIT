## Comandos para el manjeo de MD 

 -  Para añadir etiquetas , anadir una " # " adelante.
 Ejemplo:

 # Encabezado 1 (#)

 ## Encabezado 2 (##)
 
 ### Encabezado 3( ###)

 ***


 - Para añadir citas se utiliza el  " > " al comienzo del bloque de texto. Para hacer el salto de linea tambien se utiliza el mismo simbolo Ejemplo:

 >  Un país, una civilización se puede juzgar por la forma en que trata a sus animales.  — Mahatma Gandhi
 >

 > La casa es arriba

 ***
 
  ### Para añadir LISTAS  y SUBLISTAS, utilizar los simbolos : *,+,- 
  Ejemplo :

  + Uno
  - dos
  * tres 
      * cuatro
      * cinco

  1. Lista 1
  1. Lista 2
      - Lista 2.1
      - Lista  2.2  

*** 
 ### Para añadir codigos de bloque , utilizar "~". 
 Ejemplo:

 


      ~~~
      Esto es un bloque , para abrirlo añadir 3(~) y para cerrar anadir 3(~)
      ~~~

***
### Para las enfasis , utilizar asteristicos o guilones.
Ejemplo:
>
 _Cursiva:_

>
__Negrita__
>
***Cursiva y Negrita***

***

### Para añadir un  enlace, lo tienes que poner dentro de los parentesis y el texto enlazado va dentro de los corchetes.

Ejemplo:  [Web Site Plaiaundi](https://plaiaundi.hezkuntza.net/es/)

***
### Para añadir imagens , es el mismo metodo para añadir links,la diferencia , es que hay que utilizar la exclamacion y la ruta de la imagen.
Ejemplo:![Texto alternativo](C:\Users\1daw3\Pictures\
SistemaSolar.png)

***
### Y por ultimo para omitir markdown, utilizar los puntos, asteriscos sin que tengan algun efecto , es solo poner la barra invertida adelante de cualquier elemento.

Ejemplo:

* Casa
* Coche
   
   \ casa
   coche
***

## Colores : 
Agregue una clase personalizada a un encabezado o párrafo usando las siguientes clases especiales.

### GitLab Orange Heading
{: .gitlab-orange}

### GitLab Purple Heading
{: .gitlab-purple}


*** 

### Videos
Este método funciona para videos de YouTube y cualquier otro video incrustado dentro de una etiqueta <iframe>.

Copie el código a continuación y péguelo en su archivo de rebajas. Deje una línea en blanco arriba y abajo. NO edite el bloque de código (por ejemplo, elimine espacios; es posible que el iframe del video no se procese correctamente)
Vaya a la URL del video que desea mostrar
Haga clic en "Compartir", luego en "Insertar"
Copie solo la URL de <iframe>origen ( src) y péguela reemplazando lo siguiente:src

<!-- blank line -->
<figure class="video_container">
  <iframe src="https://www.youtube.com/embed/enMumwvLAug" frameborder="0" allowfullscreen="true"> </iframe>
</figure>
<!-- blank line -->

***
### Insertar Documentos
Es fácil incrustar Google Docs, Sheets, Slides y prácticamente todo lo que proporciona un iframe para usar. Lo único que debe hacer es usar el siguiente código dentro de su archivo de rebajas y reemplazar el iframe del documento que desea incrustar:

<figure class="video_container">
<iframe IFRAME CONTENT></iframe>
</figure>

<figure class="video_container">
<iframe src="https://docs.google.com/spreadsheets/d/1jAnvYpRmNu8BISIrkYGTLolOTmlCoKLbuHVWzCXJSY4/pubhtml?widget=true&amp;headers=false"></iframe>
</figure>

***







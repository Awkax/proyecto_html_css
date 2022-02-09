# proyecto_html_css
Proyecto entregado para el primer módulo del certificado de profesionalidad del SOIB

Documentación proyecto final
La empresa tiene como objetivo principal a corto/medio plazo tener presencia en internet para conseguir más clientes.
De momento no se plantea nada más que una web informativa para que los clientes contacten con la empresa.

He decidido hacer el código desde cero para que la empresa pueda ver y jactarse de mis dotes de programación, ya que es de mi padre.

Como desarrolladora he realizado un boceto:
-Una cabecera
-Un menú con enlaces a las otras páginas
-Breadcrums
-Zona de contenido
-Un footer 

CSS
He elegido una paleta de colores que he declarado al principio del CSS general, intentando así mantener la coherencia de color y sin variar la tipografía (Montserrat, de Google Fonts).

En lugar el logo de la empresa he utilizado un icono con la idea de cambiarlo en otro momento por el logo que habría que rehacer.

Con el fin de dotar al sitio web de un diseño responsivo que se adapte a cualquier dispositivo se han usado @medias y propiedades como Grid o Flexbox.

Para que el usuario pueda interactuar y le sea apacible visualmente se han empleado transiciones, sombras y algún gif.


Especificación de contenidos:
(Disclaimer: No todas las páginas tienen la misma agrupación. Por ejemplo la página de inicio no tiene breadcrums y la página de mapa de navegación no tiene breadcrums ni menú.)

El boceto de la estructura general sería así:

  -Cabecera
    En esta zona he situado una pequeña imagen del “logo” de la empresa (que por ahora es un icono) que tiene un enlace a la página de inicio. El nombre de la empresa y el slogan están inmediatamente después. Todo encima de un fondo con tres imágenes (una de archivo, una que es un overlay y una haciendo el efecto de “flecha”)

  -Menú con enlaces a otras páginas
    Menú sencillo de una lista anidada posicionado horizontalmente para que el usuario no se pierda en la propia página y sepa dónde está en todo momento.

  -Breadcrums
    Es otra herramienta para que el usuario esté orientado pero en formato breadcrums. Está sacado enteramente de https://codepen.io/dp_lewis/pen/MWYgbOY.

  -Zona de contenido
    Es la parte más importante. Contiene la información que caracteriza cada página.
Según la temática de la página hay un tipo de contenido u otro incluso un tipo de agrupación de contenido u otro.

  -Footer
    Una zona situada abajo del todo con un texto simple y un enlace hacia el mapa de navegación. También tiene tres iconos con enlaces a redes sociales.


Estructura técnica:
Consta de 8 html. 
-index.html
-nosotros.html
-origen.html
-contacto.html
.serv.html
-trabver.html
-real.html
-mapa.html


Se han usado los siguientes metas para informar a los buscadores:
<meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta name="description" content="Página de contacto de una empresa de pintura y rehabilitación integral de fachadas.">
    <meta name="keywords" content="pintura, fachadas, pintura de fachadas, reacondicionamiento, mallorca, trabajo vertical, pintura mallorca, fachadas mallorca, rehabilitación integral de fachadas, contacto">
    <meta name="author" content="Lucila Azul Muñoz Gomez">
    <meta name="robots" content="index,follow">
  

Se han usado 5 archivos css.
Uno que se llama styles.css que es el común en todas las páginas html.
Los otros 4 son:
-styles_servicios.html
-styles_contacto.html
-styles_index.html
-styles_trabajos.html

Frameworks usados:
-W3.css 
-Se han usado elementos ya hechos como si se tratara de un framework pero de otras páginas como por ejemplo codepen.io o algún elemento concreto de platillas de html5up.net.

Desde cualquier archivo se regresa perfectamente a la página inicial ya sea por breadcrums, el menú o el enlace que está en el icono de la cabecera. 

Las fotografías son de la empresa, menos algunas como el header que son de libre difusión. 

El website ha sido probado en los navegadores actuales obteniendo una visualización correcta en las versiones más recientes de los mismos.

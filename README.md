# <img src="https://github.com/micanevoran/SOLENA/blob/master/img/logo.svg" alt="SOLENA - Soluciones Energéticas Ambientales" width=25%>
<img src="https://img.shields.io/badge/STATUS-EN%20DESAROLLO-green">


## Introducción
Solena SAS es una empresa que ofrece soluciones energéticas ambientales de manera integral. Ofrece a sus clientes tanto servicios como productos, para que puedan sumergirse en el mundo verde que se viene. 

Este proyecto me entusiasma particularmente por dos razones: por un lado, es mi primer proyecto de Desarrollo Web y, por otro lado, porque se trata del emprendimiento de mi familia.

El sitio consta de 5 páginas (Index, Nosotros, Productos, Galería y Contacto) y tiene un diseño totalmente responsive. 


## Links

* Link al Repositorio: https://github.com/micanevoran/SOLENA.git

* Link a Pages de Github: https://micanevoran.github.io/SOLENA/

* Link a Host Gratuito (Netifly): https://inquisitive-kheer-0ee982.netlify.app


## Tecnologías Utilizadas:

* HTML para la estructura del sitio

* CSS para el diseño del sitio

* BOOTSTRAP para aprovechar algunos recursos y clases preestablecidas por el framework

* SASS para la optimización del código.


## Descripción sitio, sus páginas y su construcción

### ELEMENTOS COMUNES

* Nav: la barra de navegación superior fue maquetada utilizando BOOTSTRAP. Está ubicada en la parte superior de todas las páginas en posición sticky para que se pueda acceder rápidamente a cualquier parte del sitio en todo momento. Se adapta a la resolución del dispositivo en el que se visualice, haciendo uso del "hamburger button" para resoluciones menores a 1024px. En cuanto a la parte interactiva, agregué un subrayado animado a los elementos de la nav en el *hover*

* Footer: en la parte inferior de cada página, con íconos que redireccionan a las redes sociales de la empresa. Los links fueron agregados con *target:_blank* para que al hacer click en ellos, se abra una nueva pestaña con la acción requerida. En cuanto a la parte interactiva, agregué un aumento de la opacidad a los elementos del footer en el *hover* 

### INDEX

Aquí el objetivo fue dar un primer pantallazo general de la empresa. primero un *header* con un carrousel de fotos alusivas (recurso tomado de BOOTSTRAP) y un heading *h1* con el nombre de la Empresa.

Luego, la presentación de las dos líneas de productos con las que cuenta la empresa. La idea es que al hacer click en los botones, redireccione a la sección de productos, con el filtro correspondiente a la línea a la que se está accediendo. Por el momento, ante mi desconocimiento Javascript, los botones redireccionan a la página de los productos sin aplicación de filtros. 

Finalmente, se hace una presentación de clientes que ya han elegido la empresa para realizar sus trabajos, mostrando los logos de los mismos. En resoluciones menores a 1024, se muestran dos líneas con 3 clientes cada una y en resoluciones de 1024 en adelante, una sola línea con todos los clientes. La estructura fue realizada con sistema de grillas de BOOTSTRAP. En cuanto a la parte interactiva, agregué el coloreado de los logos de los clientes en el *hover*

### NOSOTROS

En la página "Nosotros" hay una foto de Eduardo Nevoran, fundador de la empresa junto a una breve reseña histórica, descripción y propuesta de la Empresa. La estructura responsive de la página fue pensada con *grids*

### PRODUCTOS

En la página "Productos" se visualizan los productos ofrecidos, con un buscador y los filtros correspondientes para facilitar búsqueda del usuario. Como se mencionó anteriormente, los filtros no funcionan, aunque espero poder hacerlo cuando adquiera los conocimientos de JavaScript. El próximo paso será confeccionar una tienda online completa en esta página. En cuanto a la parte interactiva, agregué una transformación de escalado con transición de los productos en el *hover*

La estructura responsive de la página fue pensada con *grids* y *flexbox*

### GALERÍA DE FOTOS

Aquí hay una selección de fotos de trabajos realizados por la Empresa. La estructura responsive fue pesada con *grids*, siendo útil también para el diseño asimétrico de la galería en resoluciones iguales o mayores a 1024px.

### CONTACTO

En la página de contacto hay un formulario de contacto, que aún no funciona, y un iframe de un mapa con la ubicación de la Empresa, junto a la información de contacto (teléfono y dirección). La estructura responsive de la página fue pensada con *grids* y *flexbox*.

Para el formulario se utilizaron recursos de BOOTSTRAP. 

:exclamation:**Bonus Track**: Al hacer click en el boton *Enviar* de la página de contacto, se redirecciona la página a una página personalizada de *ERROR 404*


## Consideraciones tenidas en cuenta para SEO y Optimización del Sitio

* Agregado de etiquetas *meta description*, *meta keywords* y *meta author* en todas las páginas. 

* Headers con headings *h1* en todos los HTML.

* Textos alternativos de todas las imágenes, lo más descriptivos posibles.

* Optimización de todas las imágenes del sitio, balanceando la calidad deseada con el menor peso posible. Utilización de imágenes en formato *.svg* en todos los casos que fue posible (logo de la empresa, íconos).

## Recursos SASS utilizados para Optimización del Código

### Variables

* Utilización de variables para las fuentes y el peso de la tipografía

### Map

* Utilización de un mapa para la paleta de colores utilizada en todo el Sitio

### Extend

* Definí una clase base para todos los botones y luego la extendí a los botones de las líneas de producto del Index, al botón de la lupita para buscar productos en la página "Productos" y al botón "Enviar" del formulario de contacto. 

### Mixins








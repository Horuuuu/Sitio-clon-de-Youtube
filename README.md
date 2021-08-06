# Pagina-principal-Youtube


![](img/Screenshot_1.jpg)
<h3>Resumen de proyectos y certificados de estudio</h3>
<p>Las fuentes para el logotipo son de GoogleFonts y los iconos de Font Awesome.</p>
<h4>Tres secciones</h4>
<ul><li>Header</li>
  <li>Menu lateral</li>
  <li>Contenido Principal</li>
  </ul>
  <p>El contenido de la pagina se encuentra en un contenedor. A travez de Grid template columns se divide en dos columnas , el menu lateral con un tamaño fijo y el contenido principal con el tamaño restante para cubrir cuando se cierre el menu.El header a travez de grid template areas abarca las dos columnas. A  travez de grid template rows se divide en dos filas ,una con el Header que  tiene un tamaño fijo y la otra el menu y el contenido principal abarcando el tamaño restante.</p>
  <p>Con grid template columns el Header esta dividido en tres partes . Grid template areas le da un sector a cada uno, el primero con el boton de menu y el logo ,el segundo con la barra de busqueda y el tercero con los iconos y el avatar.</p>
 
 ![](img/Screenshot_3.jpg)
<p>El contenedor cuenta con la clase active y un identificador ,con esto utilize document.Queryselector para acceder al boton del menu y un addeventlistener para el evento click que  ejecuta la funcion. La funcion ingresa a la lista de clases del contenedor y a travez del metodo toggle le da la clase active, (si no la tiene) y se la quita si la tiene.Asi el menu cambia de tamaño deacuerdo al click del usuario.</p>
El contenido principal lo hice con grid , un grid gap para que halla un espacio entre las imagenes de la grilla y un grid template columns para que tenga cuatro columnas.
<footer>Ambas paginas estan hechas con Html ,Css ,Bootstrap y Javascript</footer>

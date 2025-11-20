---
title: Acerca de
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/nav-menu.html sections="Sobre la edición;Grupo 1;Grupo 2;Grupo 3;" %}

## Sobre la edición

Este proyecto surge de la colaboración del **<a href="https://hdlab.space/" target="_blank">Laboratorio de Humanidades Digitales del CONICET</a>** y el **<a href="https://www.utdt.edu/ver_contenido.php?id_contenido=103&id_item_menu=438" target="_blank">Departamento de Estudios Históricos y Sociales</a>** de la **Universidad Torcuato Di Tella**, a través de la materia “Humanidades Digitales”. En este curso, se le propuso a los estudiantes crear una edición digital en lenguaje XML-TEI que cuente con notas al pie interactivas, locaciones georreferenciadas y material adicional como imágenes. 

## Grupo 1

**De Montevideo a Buenos Aires**

<ul>
    <li><hi>Arreguez Matias Lujan Daniel (Universidad Torcuato Di Tella)</hi></li>
    <li><hi>Courtade Maria Pilar (Universidad Torcuato Di Tella)</hi></li>
    <li><hi>Tamburro Sofia (Universidad Torcuato Di Tella)</hi></li>
    <li><hi>Terazzolo Maria Josefina (Universidad Torcuato Di Tella)</hi></li>
</ul>

El proyecto de edicion se baso en digitalizar la cronica de viaje El Lazarillo de Ciegos Caminantes del autor Alonso Carrio de la Vandera publcado en el año 1773 en la ciudad de Lima, Peru. Este libro describe el itinerario desde Montevideo hasta Lima, pasando por lugares como Buenos Aires, Cordoba y Cuzco, reflejando la vida cotidiana, las costumbres y la geografia del paisaje. En esta oportunidad, se trabajaron las secciones que incluyen desde Montevideo hasta Buenos Aires. A cada integrante se le asignaron folios especificos, sobre los cuales cada uno identifico atributos de lugares, personas y notas a traves de la plataforma Visual Studio Code. Luego, cada folio fue incorporado a un archivo TEI general que fue la base para realizar esta pagina web utilizando Jekyll y una plantilla Collection Builder.
A la hora de elaborar esta visualizacion, recurrimos a Github para hacer una copia de respaldo y tener registro de cada cambio. Ademas, a partir de una plantilla hicimos un itinerario georeferenciado con los lugares transitados de nuestra seccion. Para ultimar detalles, modificamos cuestiones esteticas del sitio web.   


## Grupo 2

**Notas a la región de Buenos Aires**

<ul>
    <li><hi><a href="https://www.linkedin.com/in/diana-h-cardozo">Diana Cardozo (Universidad Torcuato Di Tella)</a></hi></li>
    <li><hi><a href="https://www.linkedin.com/in/claragscaputo">Clara Caputo (Universidad Torcuato Di Tella)</a></hi></li>
    <li><hi><a href="https://www.linkedin.com/in/candelahalpern">Candela Halpern (Universidad Torcuato Di Tella)</a></hi></li>
    <li><hi><a href="https://www.linkedin.com/in/sabrina-lunge-070204352">Sabrina Lunge (Universidad Torcuato Di Tella)</a></hi></li>
</ul>

El presente trabajo se enmarca en la cursada de Humanidades Digitales 2025 en la Universidad Torcuato Di Tella. Su propósito fue llevar a cabo la digitalización del libro Lazarillo de Ciegos Caminantes, una obra del siglo XVII por Alonso Carrió de la Vandera que relata su recorrido por ciudades y pueblos de la América colonial. El autor fue un funcionario borbónico comisionado como visitador de correos entre 1771 y 1772 en el Virreinato del Perú y del Río de la Plata. En el transcurso de este cuatrimestre, fue posible realizar, de manera grupal y colaborativa, la edición y digitalización del apartado Nota (folios d7-g3) donde encontrar los comentarios, reflexiones y anotaciones hechos durante su pasaje por Buenos Aires.

El proceso de digitalización consistió de cuatro etapas. Como punto de partida, trabajamos con la materialidad del libro y recurrimos a la versión digitalizada del Lazarillo de Ciegos Caminantes, disponible en la Biblioteca Nacional de España, y la edición de texto plano en la Biblioteca Virtual Cervantes. A partir de la redacción en caracteres básicos y sin formato, fue posible comenzar con la transformación del texto histórico en su versión digital con el programa Visual Studio Code en lenguaje XML - TEI. 

Los folios se dividieron entre las cuatro integrantes, donde cada una realizó la codificación de la cantidad de páginas correspondientes, que luego unificamos en un único archivo XML - TEI. En esta segunda etapa,  se llevó a cabo la identificación de los párrafos y cambios de página conforme a la versión digitalizada. Como también marcar las notas, lugares, personajes y tablas relevantes dentro del archivo XML-TEI para que sean expresadas, etiquetadas y resaltadas de forma desplegable en la página web. 


Además, completamos y detallamos la descripción de los personajes y de notas según su “key” determinada en los documentos de Excel correspondientes. Para los lugares, realizamos la georeferenciación con coordenadas tomadas de Google Maps y la descripción de las localidades mencionadas en el relato. Una vez completado esto, cargamos al repositorio los documentos con las referencias utilizadas y, gracias a la extensión xslt-transform de Visual Studio Code, generamos archivos HTML con los datos almacenados en XML. Esto nos permitió construir nuestro sitio web estático con el software Jekyll desde la plataforma Git Hub y generar nuestra página web con la plantilla Collection Builder del HD LAB - CONICET para llevar adelante la publicación digital del apartado Nota. Es decir, generamos archivos HTML a partir de fichas XML-TEI, que nos permitieron visualizar nuestro sitio.  

En una tercera etapa, nos ocupamos de la visualización del texto. Para ello, realizamos el StoryMap donde registramos algunos lugares, elegimos imágenes y armamos el itinerario. Este StoryMap se integró al sitio web a modo de enriquecer la propia lectura e inmersión dentro del relato que acompañan los viajes realizados en la obra. **Ciudades, caminos, prácticas comerciales y costumbres locales. Obra híbrida: parte guía de viaje, parte documento histórico y parte relato anecdótico  Palabras claves y temas como metadatos de la página y el texto que faciliten los motores de búsqueda.** 
Finalmente, en una cuarta etapa, realizamos modificaciones en el sitio web para agregar nuestra impronta y estética. Completamos textos sobre cómo fue la edición, cambiamos la imagen de portada y elegimos una paleta de colores que nos pareció adecuada para la temática, entre otros cambios. Este proceso se realizó a lo largo de todo el cuatrimestre con el que dio fruto a nuestro sitio sobre el apartado Nota del Lazarillo de ciegos caminantes.  


## Grupo 3

**Jurisdicción de Córdoba**

<ul>
    <li><hi><a href="https://www.linkedin.com/in/emma-alvarez1/" target = "_blank">Emma Alvarez (UTDT)</a></hi></li>
    <li><hi><a href="https://www.linkedin.com/in/valentinataboada/" target = "_blank">Valentina Sol Taboada (UTDT)</a></hi></li>
    <li><hi><a href="http://linkedin.com/in/sol-cosarinsky-03b201378" target = "_blank">Sol Cosarinsky (UTDT)</a></hi></li>
    <li><hi><a href="https://www.linkedin.com/in/maria-agustina-fernz/" target = "_blank">Agustina Fernandez (UTDT)</a></hi></li>
    <li><hi><a href="https://www.linkedin.com/in/luna-feit/" target = "_blank">Luna Feit (UTDT)</a></hi></li>
</ul>

La presente edición digital consiste en el capítulo “Jurisdicción de Córdova”, del *Lazarillo de Ciegos Caminantes*, publicado en 1773 por **Alonso Carrió de la Vandera**. El texto pertenece al periodo del reformismo borbónico e intentó ser una descripción fidedigna de las colonias americanas para los lectores españoles, siendo este un género de publicación típico de la época. Este capítulo relata, en forma de crónica de viajes, el recorrido desde Córdoba hasta Santiago del Estero, donde el autor registra las distintas postas que conformaban el Camino Real en tiempos coloniales, tales como el Saladillo de Ruy Diaz, Fraile Muerto y Sinsacate.
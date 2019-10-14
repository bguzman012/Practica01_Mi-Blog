# Practica01_Mi-Blog
RESULTADO(S) OBTENIDO(S):
Se creo el repositorio llamado Practica 01_Mi-Blog, luego se clona en VS Code y se puede trabajar de forma que se realiza push y commit
“tel” ha servido para etiquetar un numero de teléfono y crea un acceso directo a llamar a ese numero.
<a href="tel:+5968420404">(+593)  968420404</a>
mailto crea un hypervinculo para el correo electrónico y al dar click sobre el mismo se abre en el programa de correos que el usuario tenga como predeterminado
<a href="mailto:bguzmanc@est.ups.edu.ec">bguzmanc@est.ups.edu.ec</a>
-Se empieza diseñando el esqueleto que va a tener nuestro documento del index
 <!DOCTYPE html>
<html lang="es">

<head>
  <title>Liga Deportiva Universitaria.</title>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />

</head>

<body>
  <header class="logo"><a href="index.html"><img src="images/Cabecera.png" alt="Liga_Corazon" /></a>
    <br />
    <nav>
      <ul>
        <li><a href="docs/general/historia.html">Historia</a></li>
        <li><a href="docs/personal_club/dirigencia.html">Dirigencia</a></li>
        <li><a href="docs/general/simbolos.html">Simbolos</a></li>
        <li><a href="docs/personal_club/hinchada.html">Hinchada</a></li>
        <li><a href="docs/general/momentos_hist.html">Momentos Historicos</a></li>
      </ul>
    </nav>
    <br />
  </header>
  
 En la pagina simbolos.html se han utilizado al menos 5 etiquetas de texto como se puede observar a continuación.
 
  <section>
    <h2>Simbolos</h2>
    <article>
        <h3>Uniforme</h3>
        <p>El Club Universitario, antecedente del equipo azucena, <b>tuvo dos uniformes</b>; el primero fue una camiseta 
        blanca con una franja diagonal roja desde el hombro derecho hasta la parte inferior izquierda, pantalón
        azul y medias blancas; el segundo creado en 1919 fue una camiseta azul con el escudo representando a la 
        Universidad Central del Ecuador, un triángulo invertido de fondo azul y rojo con las letras UC en blanco.
        Estos dos uniformes fueron utilizados de manera alternada hasta la creación oficial de Liga de Quito en 1930.</p>
        <p>Desde su re-fundación, el conjunto albo se ha caracterizado por utilizar el color blanco en su uniforme. 
        El uniforme fue idealizado en <mark>1930</mark> por Bolívar León, uno de los fundadores del club. El primer uniforme 
        tenía camiseta blanca con el escudo del club en el centro del pecho, pantalón blanco y medias azules. 
        Los colores azul y rojo, son considerados los colores secundarios del club, estos han aparecido en los 
        uniformes del equipo en pequeñas proporciones. En los últimos años, el color rojo ha prevalecido por 
        encima del color azul.</p>
      
        <h3>Estadio</h3>
        <p>A lo largo de su historia Liga de Quito ha jugado como local en el desaparecido Estadio El Ejido, 
        en el Estadio Universitario y en el Estadio Olímpico Atahualpa, en este último actuó de local hasta 
        el año 1996. Desde el año 1997 el equipo juega de local en su propio estadio.</p>
        <p>El Estadio de Liga Deportiva Universitaria, más conocido como Estadio Casa Blanca y actualmente 
        denominado <strong>Estadio Rodrigo Paz Delgado</strong>, es <cite> el segundo estadio más grande de Ecuador con una capacidad 
        de 41 575 personas reglamentariamente</cite>.</p>

<b> </b> - Para resaltar con negrita
<mark> </mark>- Para pintar de un color un suceso importante y darle énfasis
<strong> </strong> resalta un suceso importante
<cite></cite> para citar textualmente algo expuesto en otros textos
<u></u> subraya para dar un mejor enfasis

Video de youtube

Youtube nos facilita la obtención del código en html de un video cualquiera poniendo en compartir, incorporar y solo se copia el código y se pega dentro de la etiqueta <article> de la siguiente manera.

<section>
    <h2>Hinchada</h2>
    <article>
      <h2>Muerte Blanca</h2>
      <p>La barra brava más representativa del club es la Muerte Blanca, que se ubica en la parte baja de la General Sur
        del Estadio de Liga Deportiva Universitaria, mientras que la barra más antigua es Los Dinosaurios.</p>
        <aside>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/1nXT8wpvA50" 
            frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" 
            allowfullscreen> </iframe>
        <br><strong>Pasion por la U.<br></strong>
      </aside>
      <aside>         
        <img src="../../images/hinchada.jpg" alt="hinchadaa_liga" />
        <br><strong>Hinchas de Liga de Quito en Casa Blanca<br></strong>
        </aside>
    </article>
 
Manejar listas ordenadas o desordenadas con al menos cinco ítems

En este caso se ha manejado una lista ordenada con 5 items en la pagina momentos_hist.html 
Se ha utilizado la estructura de la siguiente forma:
  <section>
    <h2>La grandeza de Liga Deportivo Universitaria</h2>
    <article>
        <h3>Datos Historicos</h3>
        <ol>
                
                <li>Máximo goleador en torneos internacionales: Hernán Barcos (20 goles).</li>
                <li>Mejor puesto mundial en Ranking IFFHS: 11.° (2011).45</li>
                <li>Campeon Libertadores, Sudamerica y Recopa Sudamerica</li>
                <li>Subcameon de Mundial de clubes​.</li>
                <li>Primer ganador de una copa internacional Ecuador</li>
        </ol>

Se pide que una de las páginas tenga al menos dos secciones () con tres artículos () cada sección. Luego, cada sección debe tener un encabezado (), en donde, se ubicaran enlaces que permitan navegar entre los artículos usando id’s.
 
 
Crear una tabla
 <h3>Presidentes Campeones LDU</h3>
        <table style="width: 100%" border=1>
            <tr>
                <th rowspan="2">Presidente</th>
                <th colspan="2">Tiempo</th>
            </tr>
            <tr>
                <td>Periodo<br></td>
                <td>Titulos</td>
            </tr>
            <tr>
                <td>Telmo Ponce</td>
                <td>1969-1971</td>
                <td>Serie A 1969</td>
            </tr>
            <tr>
                <td>Raúl Vaca</td>
                <td>1974-1976 <br> 1990-1992</td> 
                <td>Serie A 1974 <br> Serie A 1975 <br>Serie A 1990</td>                        
            </tr>
            <tr>
                <td>Darío Ávila</td>
                <td>1995-2004</td>
                <td>Serie A 1998 <br> Serie A 1999 <br> Serie A 2003</td>
            </tr>
            <tr>
                <td>Alfonso Rodríguez</td>
                <td>2005-2006</td>
                <td>Serie A 2005</td>
            </tr>
            <tr>
                <td>Carlos Arroyo</td>
                <td>2007-2016</td>
                <td>Serie A 2007
                    <br>Copa Libertadores 2008
                    <br>Recopa Sudamericana 2009
                    <br>Copa Sudamericana 2009
                    <br>Recopa Sudamericana 2010
                    <br>Serie A 2010</td>
            </tr>
            <tr>
                <td>Guillermo Romero</td>
                <td>2016-presente</td>
                <td>Serie A 2018</td>
            </tr>
        <tr>
                <td colspan="3">Carlos Arroyo <em> "Presidente mas ganador"</em></td>
        </tr>

    </table>
    
Se utilizo las etiquetas <table> <tr><th><td>
Agregar Foote(Pie de Pagina)
  
  <footer>
    <i> &copy; Todos los derechos reservados &#8226; </i> <i>Bryam Wilson Guzman Cabrera &#8226; </i> <i> Universidad Politecnica Salesiana &#8226; </i>
    <a href="mailto:bguzmanc@est.ups.edu.ec"> bguzmanc@est.ups.edu.ec</a> &#8226; <a href="tel:+593968420404">(+593) 968420404</a>
  </footer>
 
&copy; - se ha utilizado para el copyright
&#8226; un separador
Datos Practica01-Mi_Blog 
Usuario- bguzman012
Link https://github.com/bguzman012/Practica01_Mi-Blog.git


Datos Curbside-Thai
Usuariobguzman012
Link https://github.com/bguzman012/Tutorial-01---Curbside-Thai.git


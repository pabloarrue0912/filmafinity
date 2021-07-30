
# FILMAFINITY

Repositorio creado para la obtecion de informacion de la pagina web **Filmafinity** si quieres saber mas de esta pagina puedes hacer click [aqui](https://www.filmaffinity.com/cl/topgen.php?genre=&fromyear=&toyear=&country=&nodoc&notvse "aqui"), la pagina fue elegida en base a la informacion que el grupo en su conjunto queria obtener, es por este motivo que elegimos filmafinity ya que nos permitia comprobar cuales eran los top de peliculas segun las criticas de expertos y de usuarios.
Luego de definir nuestra pagina web con la cual queremos trabajar podremos obtener la siguiente informacion la cual nos permitira realizar nuestro trabajo, donde destaca lo siguiente.


- 
*Titulo de la pelicula y año*
- 
*Director de la pelicula*
- 
*Notas promedio de lo usarios de filmafinity a la pelicula*
- 
*Link de la pelicula* 
- 
*cantidad de reviews*

# Metolodigia
La metodologia utilizada para la obtencion de la informacion, fue mediante lo visto en clases, en primer lugar esta el *titulo de la pelicula y su año* , donde mediante comandos de **htlml_read** y **html_nodes**  se obtuvieron los distintos titulos que segun los usarios de **Filmafinity** son los mejores donde destacan:

-  El padrino  (1972)   
- El Padrino: Parte II  (1974)
- 12 hombres en pugna  (1957)  
- La lista de Schindler  (1993)   
- Testigo de cargo  (1957) 

Estos titulos seran comparados con las otras paginas web seleccionadas para saber que titulos se encuentran en ambas paginas de puntuaciones.

#### Directores
Ademas de obtener las peliculas tambien se obtuvo los directores que participaban en estas peliculas, si bien esto no es tan importante en nuestra investigacion, nunca esta de mas saber cual es el director de las mejores peliculas de todos los tiempos, la obtencion de estos datos fue mediante **html_nodes** y **css** y mediante print, paste podemos dejar el titulo de la pelicula y su director.

#### Promedio de notas de las peliculas
Estos promedios estan en base a las distintas notas que los usuarios de *filmafinity*  y mediante estas notas podemos comparar, las distintas notas que los usarios le dan a cada pelicula, y mediante estas se da un promedio general a cada pelicula, y con esto se puntua el ranking.


#### Link de pelicula
El link de la pelicula es netamente lo que dice su nombre, es el link que nos llevara directo a cada pagina de la siguiente manera [El padrino](https://www.filmaffinity.com/cl/film809297.html "El padrino"), y asi con todas las peliculas que se encuentran en el top.

#### Reviews
Las reviews, como lo dice su nombre es la cantidad de reviews que los usuarios de filmafinity le realizaron a las peliculas, estos datos fueron extraidos mediante **htlml_nodes** con estos numeros podemos observar la cantidad de personas que puntuaron las distintas peliculas.


#### Conclusiones filmafinity
En conclusion, filmafinity es una pagina amigable y su uso es bastante facil para la mayoria de los usuarios que quisieran saber mas sobre que peliculas podrian ver, un punto debil de esta pagina, es que las notas no son otorgado por personas expertas en cine, si no que son otorgados por los mimos usuarios, por lo cual el peso del top de estas peliculas no tendria tanto peso en comparacion con otras medidas de distintas paginas.
Por otro lado tambien se pueden obtener dentro de la misma pagina web top por cada pais, de peliculas, series u otros interes al gusto del usuario.










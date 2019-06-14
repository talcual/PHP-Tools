# PHP-Tools

Herramientas para desarrolladores del mundo de PHP

 - Metatool 
 	= Es una clase escrita en PHP que permite extraer los datos de los metatags de un sitio web, para ellos
 	  utiliza la funcion file_get_contents y curl en casos de que se acceda a un sitio con ssl, utiliza el 
 	  principio del scraping para obtener la informacion y un juego de expresiones regulares para validar los 
 	  datos obtenidos.
 
 - Geocode
  = Es una sencilla funcion escrita en php que permite obtener el resultado de un geocoding en reversa desde google maps
    no solo necesita que se le pase la dirección y la key para recibir la información de a coordenada

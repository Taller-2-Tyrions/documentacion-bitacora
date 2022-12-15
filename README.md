# Bitacora del proyecto

### Semana 04/09/22
  - Primeras ideas sobre la arquitectura
  - Investigacion sobre las tecnologias a utilizar, principalmente FastAPI, Firebase, Heroku, GitHub Actions.
  - Planteo de diagramas de secuencia sobre posibles escenarios
  - Creacion de un tablero en trello para llevar cuenta de historias realizadas y en proceso


### Semana 11/09/22
 - Gateway y microservicio de Usuarios ya desplegados y comunicandose entre si
 - Aregamos primera conexion a mongo desde el microservicio de usuarios
 - Agregamos conexion a FireBase con un primer intento de registro y login de usuarios
 - Empezamos con el microservicio de Voyage
 - Inicios en el microservicio de Payments


### Semana 18/09/22
 - Avances en el microservicio de Voyage creando las base de datos correspondientes
 - Avances en el microservicio de Users incluyendo password recovery unificamos bases de datos drivers y pasajeros a directamente solo usuarios con roles, junto con este se agrega el manejo de permisos de administradores e información personal y el agregado de foto de perfil. 
 
 
### Semana 25/09/22
 - Movemos voyage a python y agregamos funcionalidades basicas de viajes para hallar choferes y conseguir precios.
 
### Semana 02/10/22
 - Avances en el microservicio de Users agregando google login y bloqueo de usuarios, más arreglo de errores varios hallados al integrar con gateway.
 - Avances en el microservicio de voyages para testear lo implementado hasta ahora luego de mover la logica del calculo de distancias a geomongo. Creamos la estructura de viaje y comenzamos a implementar un sistema de estados para las 3 entidades del microservicio.
 
 ### Semana 09/10/22
 - Avances en voyage para manejar correctamente el cambio de estados y detectar errores ante estados incorrectos, reordenamos endpoints para simpflicar el entendimiento y los nombres de los endpoints. También se agregan las reviews y denuncias para los viajes.
 
### Semana 16/10/22
 - Avances en voyage para handlear las ubicaciones de los choferes y sobre las push notifications. Implementamos un get_status para hallar el ultimo estado correspondiente a un id enviado.

### Semana 23/10/22
 - Implementamos llamados a la API de goofle maps para manejar las distancias en tiempos al cotizar los viajes.
 
 
### Semana 30/10/22
 - Inicio en el backoffice agregando la interfaz con las distintas opciones a mostrar junto con la pagina de usuarios y la de informacion de un usuario puntual.
 - Avances en el microservicio de Payments para incluir la base de datos y smart contract ya deployado.

### Semana 06/11/22
 - Avances en el microservicio de Users agregando endpoints correspondiente a los usos del administrador.
 - Creamos el microservicio pricing a partir de lo previamente hecho en voyages. Incluyendo nuevas funcionalidades como el seteo de constantes de precios.
 - Avances en el backoffice terminando parte de usuarios
 - Incluimos endpoints para obtener el balance en el microservicio de payments y arreglos de errores en el deploy y en la logica de comisiones.

### Semana 13/11/22
 - Arreglo errores en Pricing descubiertos hallados tras las integración con el backoffice
 - Iniciamos microservicio de metricas creando la base de datos.

### Semana 20/11/22
 - Avances en backoffice para incorporar la interfaz de cotizaciones.

### Semana 27/11/22
 - Llamados a Pricing desde Voyages para cotizar los viajes y arreglos en push notifications para simplificar la implementación de la app.
 - Comenzamos a implementar los endpoints de metricas y la lectura de datos desde el gateway.

### Semana 04/12/22
 - Avances finales en backoffice agregando login e interfaces faltantes de metricas y denuncias.
 - Avances en voyages para cobrar multa en caso de cancelación y cambios en los tipos de estados para clarificar el contexto de cancelacion.
 - Agregamos tests para el microservicio de metricas.

### Semana 11/12/22
 - Arreglos en Voyage para conseguir si es vip y continuamos arreglando estados en casos de cancelación.

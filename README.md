# Práctica 2

## Objetivo
El alumno aplicará los conceptos aprendidos en la materia de desarrollo de aplicaciones móviles referentes al consumo de webservices de terceros.  

## Descripción de la actividad

Crear una aplicación que nos permita consumir un api de códigos postales y nos muestre las colonias relacionadas con ese código postal.

- Se utilizará el API de Geonames para el consumo del servicio
- Para el uso del API se debe crear una cuenta en el siguiente enlace http://www.geonames.org/login
- Para habilitar el uso de la API se deberá ir al siguiente enlace y seleccionar el uso del servicio http://www.geonames.org/manageaccount. En caso de no habilitar la cuenta se recibirá un mensaje como el siguiente.

```
{"status":{"message":"user account not enabled to use the free webservice. Please enable it on your account page: http://www.geonames.org/manageaccount ","value":10}}
```

- Para verificar que tu cuenta funcione, prueba con el siguiente enlace (Reemplaza `TUUSUARIO` con el usuario que creaste): 
```
http://api.geonames.org/postalCodeSearchJSON?postalcode=38060&country=MX&maxRows=2&username=TUUSUARIO
```

- La interfaz deberá contener un campo para colocar el código postal que se desea buscar y un botón de enviar que lance la búsqueda.
- La información obtenida deberá presentarse en una Recycler View que contenga el `postalCode` y el `placeName` entregados por el webservice.
- La aplicación deberá tener una vista donde se muestren los datos del alumno, accesible desde el menú.

## Instrucciones de entrega

- Fecha limite de entrega: 12 de diciembre de 2016 antes de la hora de clase.
- La aplicación deberá estar en un repositorio privado de Github y se deberá enviar solicitud de colaboración al profesor para poder evaluarla.
- El README.md de la aplicación deberá incluir tomas de pantalla de la aplicación así como un enlace a un video donde se muestre la aplicación funcionando. El video deberá ser subido a Youtube para poder reproducirlo fácilmente.
- Se deberá realizar un reporte en formato PDF donde se explique de forma detallada como se realizó la aplicación.

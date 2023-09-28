# despliegue-de-aplicaciones-web

1. Crea un repositorio para subir todas las actividades de esta asignatura con el
nombre despliegue-de-aplicaciones-web.

2. Crea una carpeta en tu repositorio llamada “Actividad 1” y dentro crea un archivo
README.md con la solución a los siguientes ejercicios.


3. Analiza los headers de las peticiones cuando inicias sesión en el Moodle y comprende
cómo se obtiene el token. Para ello, necesitamos saber de dónde salen TODOS los
datos sensibles que se envían.

* Le daremos a Ctrl + Shift + "i".
* Iremos al apartado de "Network".
* Y por último al apartado del Token que se llama "Payload"

![image](https://github.com/killianPV/despliegue-de-aplicaciones-web/assets/144901130/01db9b87-56f0-4d6f-98c1-70f8c7f71e89)

* LoginToken:
  
Es un archivo que contiene información de autenticación para hacerlo más fácil para poder acceder a sistemas protegidos. Hacen la función de un pase de seguridad.
También pueden servir como una fuente de vulnerabilidad aunque se requiere que los administradores lo usen con mucho cuidado.

4. ¿A qué puerto se reciben normalmente las peticiones del protocolo HTTP? ¿A qué
capa del modelo TCP/IP se encuentra el protocolo HTTP? ¿Y los protocolos TCP,
UDP, e IP?

El puerto que recibe es el 80 y el protocolo:

HTTP: Se encuentra en la capa 4.
TCP: Se encuentra en la capa 4.
UPD: Se encuentra en la capa 4.
IP: Se encuentra en la capa 3.

5. ¿Cuál es el significado de la siguiente respuesta de un servidor?
HTTP/1.1 302 Found
Location: http://www.example.com/test/index2.php

El error 302 Found es porque la URL no se encuentra en esa ubicación.

6. Utilizando el filtro de captura para la interfaz de red de Wireshark, analiza la petición
al host: www.google.com. Mostrando la cabecera IP, la dirección IP de tu ordenador y
la del servidor. Comprueba que, poniendo esa IP en el navegador, accedas a Google.

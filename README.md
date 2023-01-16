# ExamenFinal-CC3S2

## Parte 1
1.

2. En un entorno de microservicios, es común utilizar un proxy inverso o un gateway de API para exponer solo los microservicios necesarios al exterior, mientras que los demás permanecen ocultos y solo son accesibles desde dentro del sistema. Estos microservicios expuestos deben estar protegidos mediante mecanismos de autenticación y autorización, así como también mediante la implementación de medidas de seguridad adicionales, como la detección de amenazas y la prevención de ataques DDoS.

3. Para solucionar este problema, se puede utilizar una arquitectura basada en eventos asíncronos, en lugar de una arquitectura basada en bloqueo de E/S. Esto significa que en lugar de asignar un subproceso durante toda la duración de la solicitud, el sistema utiliza un mecanismo de cola de eventos para manejar las solicitudes de manera asíncrona.
Cuando una solicitud llega, se coloca en una cola y es procesada por un subproceso disponible. Esto permite que varias solicitudes sean procesadas simultáneamente, sin tener que asignar un subproceso para cada una de ellas, lo que reduce el número de subprocesos necesarios para manejar una gran cantidad de solicitudes simultáneas.
Además, en una arquitectura de microservicios, se pueden utilizar patrones de comunicación asíncrona, como el patrón de cola de mensajes, para facilitar la comunicación entre los diferentes microservicios. Esto permite que los microservicios se comuniquen entre sí de manera independiente y no se bloquee entre ellos, lo que ayuda a escalar el sistema y a mejorar la disponibilidad y el rendimiento.

4. •Un enfoque común es utilizar un sistema de configuración centralizado, como una base de datos o un almacén de archivos, donde se almacena la configuración de todos los microservicios. Esta configuración se puede obtener mediante consultas a la base de datos o mediante el uso de una API.
• Un enfoque común es utilizar una herramienta de orquestación de contenedores, como Kubernetes o Docker Compose, para desplegar automáticamente las nuevas instancias de microservicios con la configuración actualizada.
Otro enfoque es utilizar un sistema de configuración distribuido, donde se actualiza la configuración en el sistema y cada instancia de microservicio se actualiza automáticamente al leer la configuración actualizada.
También se pueden utilizar scripts o herramientas para automatizar el proceso de actualización de configuración y verificar que todas las instancias se han actualizado correctamente.

5. 

6. 

## PARTE 2

Encontramos la imagen de CouchDB

![docker.search.couchdb.jgp](https://github.com/alexmzztt/ExamenFinal-CC3S2/blob/main/assets/docker.search.couchdb.jpg)

![couchdb.jgp](https://github.com/alexmzztt/ExamenFinal-CC3S2/blob/main/assets/couchdb.jgp)

![couchdb.image.jgp](https://github.com/alexmzztt/ExamenFinal-CC3S2/blob/main/assets/couchdb.image.jgp)
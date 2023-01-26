# ProblemResolve

PROBLEM RESOLVE

AUTOR 
Álvaro Hoyas Rodrigo


FASE 1:

DESCRIPCIÓN DE LA WEB
Esta página web estará pensada para resolver incidencias, de tal forma que un usuario pueda realizar solicitudes que se irán acumulando y en la que cada usuario solo tendrá visible sus solicitudes, por tanto hay una funcionalidad públida de crear incidencia y una privada para acceder a sus incidencias.
Dentro de una incidencia, cada usuario podrá comentar y añadir archivos y eso será público tanto para él como para la persona que lo va a resolver, sin embargo habrá una parte de comentarios internos que el usuario no verá y solo se podrá ver dentro de las personas que van a resolver las incidencias.

FUNCIONES PÚBLICAS: Una persona puede registrarse, ver valoraciones de otros usuarios sobre incidencias resueltas y el servicio dado, listado con el número de servicios que ofrece la web. Posibilidad de ver incidencias resueltas para que todo el mundo pueda ver ese problema sin necesidad de registrarse.

FUNCIONES PRIVADAS: Creación de incidencias, asignación de incidencias, chat interno para comunicarse técnico y usuario, listado de incidencias que tiene un usuario, estadísticas para el técnico de incidencias resueltas y asignadas.

ENTIDADES PRINCIPALES
-Incidencias(Que tendrá asociados usuarios, técnicos y mensajes).
-Usuarios(Puede ser cliente o técnico).
-Mensajes(Se crearán dentro de incidencias para comunicación entre cliente y técnico).

FUNCIONALIDADES INTERNAS:

-Servicio que manda un mensaje al correo asociado cuando se comenta la incidencia o hay algún cambio en esta.
-Listado de incidencias(abiertas, cerradas o sin asignar), que se procesará a través de una base de datos.
-Posibilidad de subir imágenes cómo aclaración de la incidencia.

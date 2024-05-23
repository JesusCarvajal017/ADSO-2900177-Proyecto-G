> [!NOTE]
> Es un prototipo basico del proyecto G

# Proyecto de graduación

### 1. Planificación 
En los últimos años se ha visto un incremento de la presencia 
de las tecnologías de la información y las comunicaciones en 
nuestra vida cotidiana, esto sumado al hecho de que en la 
actualidad la mayoría de las personas cuenta 
con un celular inteligente se vio la oportunidad de resolver uno 
de los problemas que siempre ha estado presente en diferentes 
partes del mundo y también se ve presente en Neiva esta problemática es la falta de acceso a 
información en tiempo real sobre el estado de las rutas pues 
esto puede generar en los usuarios estrés, ineficiencia en la 
planificación, pérdida de tiempo, dependencia de alternativas 
de transporte, desigualdad en el acceso y menor confianza en 
el transporte público, esta problemática también influye en las 
empresas dueñas de estos vehículos pues no le pueden dan una 
correcta gestión a estos.
Estos tiempos de espera tan excesivos cobra una alta factura a 
la estabilidad mental de los usuarios del transporte público, lo 
que terminan por desarrollar estrés debido a los largos viajes, 
tiempos de espera y las condiciones inseguras de este mismo.
La Asociación Americana de Psicología [2]explica que el 
estrés crónico contribuye a la aparición de padecimientos 
graves como enfermedades cardíacas, depresión y obesidad.

Para desarrollar la solución a esta problemática se piensa desarrollar
un sistema multiplataforma de una aplicaciones movil y una 
página web utilizando APIs de geolocalización y base de datos 
para hacer una integración de pasajeros, conductores y 
empresa

### 2. Análisis de Requerimientos

#### Requerimientos Funcionales:
*	Módulo de Geolocalización
    1.	 El sistema debe poder rastrear la ubicación en tiempo real de todos los buses de la flota.
    2.	El sistema debe mostrar las rutas de los buses en un mapa interactivo.
    3.	Los usuarios deben poder ver la ubicación actual de los buses y el tiempo estimado de llegada (ETA) a las paradas.
*	Módulo de Planificación de Rutas
    1.	El sistema debe permitir a los usuarios ingresar su punto de origen y destino para planificar un viaje.
    2.	 El sistema debe proporcionar opciones de rutas óptimas basadas en el tiempo de viaje.
    3.	 El sistema debe actualizar automáticamente las rutas en caso de cambios en el tráfico o desvíos imprevistos.
*	Módulo de Notificaciones
    1.	El sistema debe enviar notificaciones push a los usuarios sobre la llegada inminente de los buses a sus paradas.
    2.	 El sistema debe alertar a los usuarios sobre retrasos, desvíos o cualquier incidente que afecte el servicio.
*	Módulo de Administración
    1.	 Los administradores deben poder agregar, eliminar y modificar las rutas de buses.
    2.	 Los administradores deben poder acceder a informes y análisis de datos sobre el rendimiento de las rutas y el cumplimiento de horarios.

#### Requerimientos No Funcionales: 
* Desempeño
    1.	 El sistema debe procesar y actualizar la ubicación de los buses en tiempo real con una latencia máxima de 5 segundos.
    2.	 La aplicación debe ser capaz de manejar hasta 1000 usuarios concurrentes sin degradar el rendimiento.
* Seguridad
    1.	 La transmisión de datos entre los dispositivos GPS y el servidor debe estar encriptada para evitar intercepciones.
    2.	Los usuarios deben autenticarse mediante un sistema de inicio de sesión seguro.
* Usabilidad
    1.	La interfaz de usuario debe ser intuitiva y fácil de usar tanto en la aplicación móvil como en la web.

* Mantenimiento
    1.	 El sistema debe ser modular para facilitar la adición de nuevas funciones o la modificación de las existentes.
    2.	 Debe existir documentación detallada del sistema para el soporte y mantenimiento continuo.

#### Requerimientos Funcionales Adicionales
*	Módulo de Integración
    1.	Debe permitir la exportación e importación de datos en formatos estándar como CSV, JSON y XML para su uso en otros sistemas de análisis.
*	Módulo de Feedback del Usuario
    1.	 El sistema debe permitir a los usuarios proporcionar feedback sobre el servicio, como la puntualidad, comodidad y condiciones de los buses.
    2.	Debe haber un sistema para que los administradores respondan a las sugerencias y quejas de los usuarios de manera eficiente.
*	Módulo de Información Adicional
    1.	 El sistema debe mostrar información adicional sobre cada ruta, como el número de bus, el conductor, capacidad del bus y paradas próximas.
    2.	 Debe proporcionar datos históricos de rutas para análisis y mejora continua del servicio.



## Riesgos y Contramedidas

Posibles riesgos durante el desarrollo del proyecto o que se descubran posteriormente, y las respectivas contramedidas para mitigarlos:

- **Riesgo de pérdida de datos**: Los datos almacenados en la plataforma podrían perderse debido a errores humanos, fallos del sistema o ataques externos.
  - **Contramedida**: Implementar un sistema de respaldo automático diario y semanal, con almacenamiento en la nube o servidores externos. Además, utilizar transacciones en la base de datos para asegurar la integridad de los datos durante actualizaciones.

- **Riesgo de bajo rendimiento**: La plataforma web podría volverse lenta debido a un uso intensivo de memoria o a la carga de consultas complejas sobre grandes volúmenes de datos.
  - **Contramedida**: Optimizar las consultas a la base de datos, utilizando paginación y almacenamiento en caché. Implementar un balanceo de carga en el servidor para distribuir las solicitudes entre varios nodos.

- **Riesgo de sobrecarga en el servidor**: Un incremento en la cantidad de usuarios concurrentes puede sobrecargar el servidor y hacer que la plataforma se vuelva inaccesible.
  - **Contramedida**: Utilizar una infraestructura escalable en la nube (como AWS o Azure), que permita aumentar automáticamente la capacidad del servidor en función de la demanda.

- **Riesgo de incompatibilidad con navegadores**: La aplicación web podría no funcionar correctamente en algunos navegadores o dispositivos debido a problemas de compatibilidad.
  - **Contramedida**: Realizar pruebas exhaustivas de compatibilidad en los principales navegadores (Chrome, Firefox, Edge, Safari) y dispositivos móviles. Usar frameworks y tecnologías que soporten diseño responsivo y compatibilidad con navegadores antiguos.

- **Riesgo de falta de adopción por parte de los usuarios**: Los usuarios podrían tener dificultades para adoptar el sistema si la interfaz no es suficientemente intuitiva o si no se proporciona soporte adecuado.
  - **Contramedida**: Realizar pruebas de usabilidad con usuarios potenciales durante el desarrollo y ajustar la interfaz de usuario en función de sus comentarios. Además, ofrecer tutoriales y una sección de preguntas frecuentes (FAQ) dentro de la plataforma.



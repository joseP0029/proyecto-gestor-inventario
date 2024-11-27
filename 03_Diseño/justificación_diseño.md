###Justificación del Diseño###

Las decisiones de diseño tomadas en este proyecto han sido guiadas por los principios de simplicidad, asegurando que el sistema de gestión de inventario cumpla con los requisitos de manera eficiente. A continuación, se detalla la justificación de las tecnologías y consideraciones de seguridad adoptadas en este proyecto: 

- Programación Orientada a objetos 

Se optó por una arquitectura basada en clases siguiendo el paradigma de la POO, lo cual permite estructurar el sistema en entidades claras lo cual facilita la reutilización de código, el mantenimiento del sistema y la extensión futura de funcionalidades, manteniendo la cohesión y modularidad del software. 

- Arquitectura Cliente-Servidor 

Se decidió implementar una arquitectura de cliente-servidor, una solución ampliamente adoptada en sistemas web. Esto permite una separación de funcionalidades, donde el cliente interactúa con una interfaz amigable, mientras que el servidor procesa las solicitudes y se comunica con la base de datos para gestionar el inventario. Esta arquitectura garantiza una mayor escalabilidad, ya que permite añadir más usuarios sin afectar significativamente el rendimiento gracias a su sencillez y partición de responsabilidades. 

- FrontEnd 

El lado cliente será desarrollado usando tecnologías basicas como HTML, CSS y JavaScript, proporcionando una interfaz accesible y fácil de usar. Para mejorar la experiencia de usuario y facilitar el desarrollo, se ha considerado el uso de frameworks modernos como React, que permiten crear interfaces dinámicas y reactivas. 

- BackEnd 

Se utilizará Java con Spring Boot para construir el backend. Spring Boot es conocido por su facilidad para desarrollar aplicaciones web rápidas y escalables, con un excelente manejo de la seguridad y la integración con bases de datos. 

- Base de Datos 

PostgreSQL ha sido elegida como la base de datos principal debido a su robustez, soporte para operaciones complejas, y capacidad para manejar grandes volúmenes de datos. 

- Seguridad  

La seguridad del sistema es una prioridad, especialmente porque se manejan datos sensibles como la información de los usuarios y proveedores. Se implementará un sistema de autenticación para gestionar sesiones de usuario de forma segura, asegurando que solo los usuarios autorizados puedan acceder y modificar los datos. 

Todos los datos sensibles, como las contraseñas de usuario, serán almacenados en la base de datos de forma cifrada, utilizando algoritmos de hash seguros. Esto garantizará que, en caso de una violación de seguridad, los datos confidenciales no puedan ser comprometidos fácilmente.

# Análisis de Requerimientos

Este análisis describe las necesidades del sistema, enfocándose en lo que el usuario final espera y necesita de la aplicación.

## Objetivos del Sistema

El sistema tiene como objetivo permitir a pequeños negocios y particulares gestionar su inventario de manera sencilla y eficiente, ofreciendo funcionalidades avanzadas y seguridad para proteger su información. Provee confianza en el almacenamiento de datos mediante una interfaz intuitiva, accesible desde cualquier dispositivo con conexión a internet, y funcionalidades que cubren la administración de productos, categorías, proveedores y reportes.

El sistema se basa en ofrecer una plataforma web, donde los usuarios podrán realizar todas las operaciones de manera eficiente y segura, sin necesidad de conocimientos técnicos avanzados.

La visión del proyecto es convertirse en una opción reconocida y confiable entre usuarios sin experiencia técnica, brindándoles una solución eficaz y accesible para la gestión de inventarios. Con la meta de aumentar su popularidad y lograr una amplia adopción, se busca que el sistema llegue a una gran cantidad de negocios y usuarios, impulsando su crecimiento en el mercado local.

### Usuarios del Sistema

- **Administrador**: Usuario con acceso completo para gestionar el inventario, roles, usuarios, categorías y proveedores.
- **Usuario común**: Usuario con permisos restringidos según su rol, limitado a la consulta de productos y reportes de stock.

## Requerimientos Funcionales

Estos son los requerimientos que definen las funciones que el sistema debe ofrecer:

### Gestión de productos
- **RF1**: El sistema debe permitir la creación de nuevos productos con campos como nombre, descripción, precio, cantidad en stock, categoría y proveedor.
- **RF2**: Los usuarios deben poder consultar la lista de productos, filtrando por categoría, proveedor o estado de stock.
- **RF3**: El sistema debe permitir la modificación de la información de un producto existente. Así como la eliminación del producto mismo.
- **RF4**: El sistema debe permitir realizar todas estas acciones a traves de una interfaz minimalista e intuitiva, con elemntos llamativos y descriptivos.

### Gestión de categorías
- **RF5**: El sistema debe permitir la creación, modificación y eliminación de categorías de productos a las cuales vincular los productos.
- **RF6**: El sistema debe permitir el uso de múltiples categorias sobre el mismmo producto para dar una mayor profundidad, facilitando y agilizando el filtrado de los elementos.

### Gestión de proveedores
- **RF7**: El sistema debe permitir la creación, modificación y eliminación de proveedores, además de su asignación a los productos.
- **RF8**: El sistema debe permitir crear perfiles para añadir información relevante y necesaria para la comunicación y mediación con los proveedores.

### Control de stock
- **RF9**: El sistema debe actualizar automáticamente la cantidad en stock de los productos tras su compra o reabastecimiento.
- **RF10**: El sistema debe mostrar una alerta en la interfaz cuando un producto alcanza una cantidad mínima de stock.

### Gestión de usuarios y roles
- **RF11**: El sistema debe permitir la creación de diferentes tipos de usuarios con permisos específicos (administrador y usuario común).
- **RF12**: Los administradores deben poder gestionar los roles de los usuarios.

### Reportes
- **RF13**: El sistema debe generar reportes de productos por categoría, productos bajo stock mínimo y reportes de proveedores.
- **RF14**: El sistema debe generar reportes de ventas de productos, mostrando los más vendidos en un periodo de tiempo y aquellos que se agotan más rápido.

### Gestión en entorno web
- **RF15**: El sistema debe permitir el acceso a través de inicio sesión desde cualquier dispositivo con conexión a internet por medio de navegadores web.
- **RF17**: El sistema debe permitir notificaciones automáticas a los usuarios sobre cambios importantes en el inventario, como productos agotados o actualizaciones de stock.

## Requerimientos No Funcionales

Estos definen las características del sistema relacionadas con su calidad y rendimiento:

### Usabilidad
- **RNF1**: El sistema debe ser fácil de usar para usuarios sin conocimientos técnicos, con una interfaz gráfica intuitiva y accesible desde dispositivos móviles y de escritorio.

### Escalabilidad
- **RNF2**: El sistema debe ser capaz de crecer en términos de número de productos, usuarios y proveedores sin perder rendimiento, utilizando una arquitectura web escalable.

### Seguridad
- **RNF3**: El sistema debe garantizar que solo usuarios autorizados puedan acceder a la aplicación y realizar modificaciones.
- **RNF4**: Los datos sensibles de los usuarios deben estar protegidos con contraseñas seguras, autenticación de dos factores (2FA) y cifrado de datos tanto en tránsito como en reposo.

### Rendimiento
- **RNF5**: Las consultas a la base de datos, especialmente en la búsqueda de productos, deben realizarse en un tiempo mínimo aceptable, optimizando el acceso desde múltiples dispositivos simultáneamente.

### Disponibilidad
- **RNF6**: El sistema debe estar disponible para su uso sin interrupciones en todo momento para su uso.

### Compatibilidad
- **RNF7**: El sistema debe ser compatible con los principales navegadores web (Chrome, Firefox, Edge, Safari) y ajustarse de forma responsiva a diferentes tamaños de pantalla.


# Análisis de Requerimientos

Este análisis describe las necesidades del sistema, enfocándose en lo que el usuario final espera y necesita de la aplicación.

## Objetivos del Sistema

El sistema tiene como objetivo permitir a pequeños negocios y particulares gestionar su inventario de manera sencilla y eficiente, ofreciendo 
funcionalidades avanzadas y seguridad para proteger su información y proveer confianza en el almacenamiento de sus datos
con una interfaz intuitiva y funcionalidades que cubren la administración de productos, categorías, proveedores y reportes.

La visión del proyecto es convertirse en una opción reconocida y confiable entre usuarios sin experiencia técnica, brindándoles una solución 
eficaz y accesible para la gestión de inventarios. Con la meta de aumentar su popularidad y lograr una amplia adopción, se busca que 
el sistema llegue a una gran cantidad de negocios y usuarios, impulsando su crecimiento en el mercado local.

### Usuarios del Sistema

- **Administrador**: Usuario con acceso completo para gestionar el inventario, roles, usuarios, categorías y proveedores.
- **Usuario común**: Usuario con permisos restringidos, limitado a la consulta de productos y reportes de stock.

## Requerimientos Funcionales

Estos son los requerimientos que definen las funciones que el sistema debe ofrecer:

### Gestión de productos
- **RF1**: El sistema debe permitir la creación de nuevos productos con campos como nombre, descripción, precio, cantidad en stock, categoría y proveedor.
- **RF2**: Los usuarios deben poder consultar la lista de productos, filtrando por categoría, proveedor o estado de stock.
- **RF3**: El sistema debe permitir la modificación de la información de un producto existente.
- **RF4**: El sistema debe permitir eliminar un producto.

### Gestión de categorías
- **RF5**: El sistema debe permitir la creación, modificación y eliminación de categorías de productos.
- **RF6**: Los productos deben estar vinculados a una categoría.

### Gestión de proveedores
- **RF7**: El sistema debe permitir la creación, modificación y eliminación de proveedores.
- **RF8**: Los usuarios deben poder asignar proveedores a los productos.

### Control de stock
- **RF9**: El sistema debe actualizar automáticamente la cantidad en stock de los productos tras su compra o reabastecimiento.
- **RF10**: El sistema debe mostrar una alerta cuando un producto alcanza una cantidad mínima de stock.

### Gestión de usuarios y roles
- **RF11**: El sistema debe permitir la creación de diferentes tipos de usuarios con permisos específicos (administrador y usuario común).
- **RF12**: Los administradores deben poder gestionar los roles de los usuarios.

### Reportes
- **RF13**: El sistema debe generar reportes de productos por categoría, productos bajo stock mínimo y reportes de proveedores.
- **RF14**: El sistema debe generar reportes de ventas de productos, mostrando los más vendidos en un periodo de tiempo y aquellos que se agotan más rápido.

## Requerimientos No Funcionales

Estos definen las características del sistema relacionadas con su calidad y rendimiento:

### Usabilidad
- **RNF1**: El sistema debe ser fácil de usar para usuarios sin conocimientos técnicos, con una interfaz gráfica intuitiva y accesible.

### Escalabilidad
- **RNF2**: El sistema debe ser capaz de crecer en términos de número de productos, usuarios y proveedores sin perder rendimiento.

### Seguridad
- **RNF3**: El sistema debe garantizar que solo usuarios autorizados puedan acceder a la aplicación y realizar modificaciones.
- **RNF4**: Los datos sensibles de los usuarios deben estar protegidos con contraseñas y cifrado de datos.

### Rendimiento
- **RNF5**: Las consultas a la base de datos, especialmente en la búsqueda de productos, deben realizarse en un tiempo mínimo aceptable.

### Mantenibilidad
- **RNF6**: El sistema debe estar desarrollado con buenas prácticas de programación para facilitar su mantenimiento y futuras actualizaciones.

### Disponibilidad
- **RNF7**: El sistema debe estar disponible para su uso sin interrupciones durante las horas laborales de los usuarios.

## Riesgos y Contramedidas

Posibles riesgos durante el desarrollo del proyecto o que se descubran posteriormente:

- **Riesgo de pérdida de datos**: Por error humano o fallo del sistema.
  - **Contramedida**: Implementar un sistema de respaldo automático para tener una copia de los datos en caso de error.

- **Riesgo de bajo rendimiento**: Por uso excesivo de la memoria.
  - **Contramedida**: Optimizar el programa reduciendo el costo de las consultas, reportes y transacciones de grandes cantidades de datos.

## Recursos

Estos son los recursos disponibles o necesarios para la realización del proyecto:

- **Recurso Humano**:
  - **Desarrollo**: El proyecto contará con una persona encargada del desarrollo del código, con los conocimientos necesarios en el software a utilizar.
  - **Interfaz y Diseño**: El proyecto contará con una persona encargada del diseño de la aplicación y del desarrollo de la interfaz gráfica, con los conocimientos necesarios en las herramientas de diseño y del softwate necesario.
  - **Seguridad**: El proyecto contará con una pesona con los conocimientos para implementar seguridad en el sistema y protección de datos.
  
- **Recurso Tecnológico**:
  - **Hardware**: Serán necesarios contar con equipos necesarios para el desarrollo del software que tengan la fluidez necesaria para llevar a cabo el desarrollo y las pruebas del proyecto.
  - **Software**: Herramientas de desarrollo como IDEs, gestores de versiones, etc, y un gestor de base de datos para la administración de la información. Además de las herramientas de diseño para el prototipado de la interfaz y creación de los diseños.

- **Recurso de Tiempo**: El tiempo estimado para el desarrollo se presenta en el siguiente cronograma:
  - Análisis: 2 Semanas.
  - Diseño: 3 Semanas.
  - Desarrollo: 8 Semanas.
  - Pruebas: 3 Semanas.

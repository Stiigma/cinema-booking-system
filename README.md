# Sistema de Reservación de Películas

Se requiere construir un sistema backend para un servicio de reservación de películas. El servicio permitirá a los usuarios registrarse, iniciar sesión, explorar películas, reservar asientos para funciones específicas y gestionar sus reservaciones. El sistema contará con autenticación de usuarios, gestión de películas y funciones, funcionalidad de reservación de asientos y reportes de reservaciones.

## Objetivo

El objetivo de este proyecto es ayudarte a comprender cómo implementar lógica de negocio compleja, es decir, la reservación de asientos y la programación de funciones, pensando en el modelo de datos, sus relaciones y en consultas complejas.

## Requerimientos

Hemos dejado fuera detalles de implementación para animarte a pensar en el diseño y la implementación del sistema. Sin embargo, aquí hay algunos requerimientos que puedes considerar:

### Autenticación y Autorización de Usuarios
- Los usuarios deben poder registrarse e iniciar sesión.
- Debes manejar roles para los usuarios, como administrador y usuario regular.
- Los administradores podrán gestionar películas y funciones.
- Los usuarios regulares podrán reservar asientos para una función.
- Puedes crear el administrador inicial utilizando datos semilla.
- Solo los administradores podrán promover otros usuarios a administradores y realizar acciones relacionadas con la gestión de películas, reportes, etc.

### Gestión de Películas
- Los administradores podrán agregar, actualizar y eliminar películas.
- Cada película debe tener título, descripción e imagen de cartel.
- Las películas deben estar categorizadas por género.
- Las películas deben tener funciones disponibles.

### Gestión de Reservaciones
- Los usuarios podrán obtener la lista de películas y sus funciones para una fecha específica.
- Los usuarios podrán reservar asientos para una función, ver los asientos disponibles y seleccionar los que deseen.
- Los usuarios podrán ver sus reservaciones y cancelarlas (solo las próximas).
- Los administradores podrán ver todas las reservaciones, la capacidad y los ingresos.

### Consideraciones de Implementación
- Piensa en el modelo de datos y en las relaciones entre las entidades.
- Considera cómo evitar la sobreventa de boletos y cómo manejar la reservación de asientos.
- Reflexiona sobre cómo manejar la programación de funciones.
- Define cómo generar reportes de reservaciones.
- Establece cómo manejar la autenticación y autorización de los usuarios.

Este proyecto es bastante complejo y requerirá que pienses en el diseño e implementación del sistema. Puedes usar cualquier lenguaje de programación y base de datos de tu elección. Se recomienda usar una base de datos relacional como **MySQL** o **PostgreSQL**.  

Una vez que hayas terminado este proyecto, tendrás un buen entendimiento de cómo implementar lógica de negocio compleja, pensar en el modelo de datos y sus relaciones, y consultas complejas. También podrás extender este proyecto agregando más características como procesamiento de pagos, notificaciones por correo electrónico, entre otras.


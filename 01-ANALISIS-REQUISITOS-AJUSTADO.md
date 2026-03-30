# Análisis de Requisitos Ajustado

## Análisis Funcional

### RF-001: Registro de Usuario  
El sistema permitirá el registro de usuarios mediante correo electrónico y contraseña. Además, se incluirá un sistema de verificación de correo para asegurar la autenticidad del usuario.

### RF-002: Login  
Los usuarios podrán acceder al sistema proporcionando su correo electrónico y contraseña. Se implementará un mecanismo de recuperación de contraseña en caso de olvido.

### RF-003: Gestión de Productos  
El sistema permitirá a los usuarios añadir, modificar y eliminar productos en su lista de seguimiento. Los productos estarán asociados a los usuarios registrados.

### RF-004: Notificaciones  
Los usuarios recibirán notificaciones acerca de cambios de estado en sus productos (e.g., bajada de precios, oferta limitada).

### RF-005: Visualización de Productos  
Los usuarios podrán visualizar los productos en un formato amigable, que muestre información relevante como precio, disponibilidad y descripción.

### RF-006: Historial de Actividad  
El sistema mantendrá un registro del historial de actividad del usuario, mostrando productos consultados y acciones realizadas.

### RF-007: Soporte al Usuario  
A través de la aplicación, los usuarios podrán contactar soporte en caso de dudas o problemas que se les presenten.

## Análisis No Funcional

### RNF-001: Rendimiento  
La aplicación deberá cargar y mostrar datos en menos de 3 segundos bajo condiciones normales de red.

### RNF-002: Escalabilidad  
La arquitectura del sistema permitirá la incorporación de nuevas funcionalidades sin afectar el rendimiento general de la aplicación.

### RNF-003: Seguridad  
Se implementarán estándares de seguridad para proteger la información del usuario, incluyendo cifrado de contraseñas y encriptación de datos sensibles.

### RNF-004: Usabilidad  
La interfaz de usuario deberá ser intuitiva, facilitando el uso del sistema sin necesidad de capacitación previa.

### RNF-005: Mantenibilidad  
El código se desarrollará utilizando estándares de codificación que faciliten su mantenimiento y futuras modificaciones.

### RNF-006: Compatibilidad  
La aplicación será compatible con las versiones más recientes de Android, realizando pruebas en diversas versiones para asegurar el correcto funcionamiento.

## Planificación Realista del Proyecto  
El plazo para el desarrollo del proyecto será desde el 17 de Febrero hasta el 31 de Mayo de 2026. Se propone un cronograma de 12 semanas que incluye las siguientes fases:

- **Conceptualización (2 semanas)**: Definición de la visión del proyecto, recopilación de requisitos y planificación general.
- **Diseño (3 semanas)**: Elaboración de prototipos de la UI/UX y diseño de la arquitectura de software.
- **Desarrollo (5 semanas)**: Implementación del sistema incluyendo la configuración del entorno, desarrollo de módulo de usuario, gestión de productos y notificaciones.
- **Pruebas y Ajustes (2 semanas)**: Realización de pruebas funcionales y no funcionales para asegurar la calidad del producto.

## Análisis de Riesgos  
- **Riesgo 1: Retrasos en el cronograma.**  
  Mitigación: Revisión semanal del progreso y ajuste del cronograma si es necesario.
- **Riesgo 2: Problemas técnicos no anticipados.**  
  Mitigación: Investigación de tecnologías y evaluación de prototipos en fases tempranas.
- **Riesgo 3: Baja aceptación de usuarios.**  
  Mitigación: Validación de la idea mediante encuestas y feedback de usuarios antes del lanzamiento final.

## Criterios de Aceptación  
Para considerar el proyecto como finalizado, se deberá cumplir con lo siguiente:
1. Todos los requisitos funcionales y no funcionales deben estar implementados y validados.
2. El sistema deberá pasar todas las pruebas funcionales y de usabilidad.  
3. La satisfacción del usuario debe ser mayor al 80% en las encuestas post-lanzamiento.
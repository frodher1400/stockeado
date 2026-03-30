# Necesidades de Hardware y Software para la Aplicación Android STOCKEADO

## 1. Resumen del Proyecto
La aplicación STOCKEADO es una herramienta diseñada para gestionar inventarios y facilitar el seguimiento de productos. Este documento detalla las necesidades de hardware y software para su desarrollo y ejecución, así como las elecciones de infraestructura y su justificación.

## 2. Necesidades de Hardware
- **Dispositivos móviles:**
  - Requerimiento: Teléfonos o tabletas Android con al menos 2 GB de RAM.
  - Justificación: Se necesita suficiente RAM para ejecutar la aplicación de manera fluida y manejar múltiples procesos simultáneamente.

- **Servidores:**
  - Requerimiento: Servidores en la nube que soporten el backend de la aplicación.
  - Justificación: La computación en la nube permite escalar recursos según sea necesario. Utilizaremos un servidor de bajo costo para comenzar, con la opción de expandir en el futuro.

## 3. Necesidades de Software
- **Sistema Operativo:**
  - Android 5.0 o superior.
  - Justificación: Las versiones más recientes de Android tiene mejoras en rendimiento y seguridad que son necesarias para una buena UX y protección de datos.

- **Lenguaje de Programación:**
  - Kotlin (preferido) y/o Java.
  - Justificación: Kotlin es más moderno y tiene características que simplifican el desarrollo en comparación con Java.

- **Base de Datos:**
  - Firebase Firestore o SQLite.
  - Justificación: Firestore permite sincronización en tiempo real, mientras que SQLite es una opción más ligera para almacenamiento local.

## 4. Elecciones de Infraestructura
- **Google Firebase:**
  - Servicios como autenticación de usuarios, base de datos en tiempo real y alojamiento de funciones.
  - Justificación: Ofrece un nivel gratuito que es suficiente para un proyecto académico, permitiendo escalar en caso de ser necesario.

## 5. Presupuesto de Nivel Gratuito
- **Firebase:**
  - Presupuesto: Gratuidad en los primeros niveles hasta ciertos límites (almacenamiento, autenticaciones, etc.).
  - Uso: Se espera no exceder los límites de uso gratuito en esta etapa inicial.

## 6. Consideraciones Finales
Este documento establece las bases para el desarrollo del proyecto STOCKEADO, asegurando que se utilicen recursos de manera eficiente y económica mientras se cumplen las expectativas del proyecto académico.
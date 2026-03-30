# Diseño de Base de Datos para el Proyecto STOCKEADO

## Introducción
Este documento proporciona un diseño completo de la base de datos para el proyecto STOCKEADO, incluyendo diagramas de entidad-relación y scripts SQL para la base de datos Room, así como la configuración de Firebase Firestore.

## Diagrama de Entidad-Relación (ERD)
![Diagrama ERD](ruta/a/tu/diagrama.png)

## Script SQL para Room Database

```sql
CREATE TABLE usuarios (
    id INTEGER PRIMARY KEY AUTOINCREMENT,
    nombre TEXT NOT NULL,
    email TEXT NOT NULL UNIQUE
);

CREATE TABLE productos (
    id INTEGER PRIMARY KEY AUTOINCREMENT,
    nombre TEXT NOT NULL,
    precio REAL NOT NULL,
    cantidad INTEGER NOT NULL
);

CREATE TABLE transacciones (
    id INTEGER PRIMARY KEY AUTOINCREMENT,
    usuario_id INTEGER,
    producto_id INTEGER,
    cantidad INTEGER NOT NULL,
    FOREIGN KEY(usuario_id) REFERENCES usuarios(id),
    FOREIGN KEY(producto_id) REFERENCES productos(id)
);
```

## Configuración de Firebase Firestore

Para configurar Firebase Firestore para el proyecto STOCKEADO, siga estas instrucciones:  
1. Visite la consola de Firebase y cree un nuevo proyecto.  
2. En la sección Firestore Database, haga clic en "Crear base de datos".  
3. Seleccione el modo de prueba o el modo de producción según sea necesario.  
4. Defina las reglas de seguridad adecuadas para su aplicación.  

### Ejemplo de Reglas de Seguridad
```json
service cloud.firestore {
  match /databases/{database}/documents {
    match /usuarios/{usuario} {
      allow read, write: if request.auth != null;
    }
    match /productos/{producto} {
      allow read: if true;
      allow write: if request.auth != null;
    }
  }
}
```

## Conclusión
Este diseño proporciona una base sólida para el desarrollo de la aplicación STOCKEADO, con un enfoque en la escalabilidad y la seguridad.
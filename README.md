# 🚀 FOROHUB



## 📄 DESCRIPCIÓN DEL PROYECTO

ForoHub es una API REST CRUD que permite la gestión de tópicos de discusión. Los usuarios pueden:

- Crear un tópico con título, mensaje, fecha, estado, autor y curso.
- Leer todos los tópicos o uno en específico.
- Actualizar la información de un tópico.
- Eliminar un tópico.

Los datos se almacenan en una base de datos MySQL y se manejan mediante Flyway Migration para el control de versiones. Se requiere Postman o Insomnia para probar las solicitudes HTTP en formato JSON.

## ✅ DEMOSTRACION

## 🔨 ESTADO DEL PROYECTO

🚧 PROYECTO EN CONSTRUCCIÓN.

## ⚙️ FUNCIONALIDADES

- **REGISTRAR TÓPICO**: Guarda un nuevo tópico en la base de datos.
- **LISTAR TÓPICOS**: Muestra todos los tópicos registrados.
- **CONSULTAR UN TÓPICO**: Obtiene un tópico específico por su ID.
- **ACTUALIZAR UN TÓPICO**: Modifica la información de un tópico existente.
- **ELIMINAR UN TÓPICO**: Borra un tópico mediante su ID.
- **CONECTAR A LA BASE DE DATOS**: Uso de MySQL con configuración adaptable en `application.properties`.
- **AUTENTICACIÓN Y SEGURIDAD**: Implementación de Spring Security con autenticación JWT.

## 🚀 USO DEL PROYECTO

Para utilizar la API, configura la base de datos en `application.properties` con:

```properties
DATASOURCE_URL=jdbc:mysql://localhost:tu_base_de_datos
DATASOURCE_USERNAME=tu_nombre_de_usuario
DATASOURCE_PASSWORD=tu_contraseña
api.security.secret=tu_clave_secreta
```

Para encriptar contraseñas usa [Bcrypt Encrypt](https://www.browserling.com/tools/bcrypt).

## 🛠️ TECNOLOGÍAS UTILIZADAS

- **Java 17**
- **Spring Boot 3**
- **Maven**
- **Spring Web, Data JPA, DevTools, Security**
- **Lombok**
- **Flyway Migration**
- **MySQL Workbench**
- **Insomnia**

## 👨‍💻 DESARROLLADO POR

**Jonathan Ariel Archila Rincón**

## 🏆 CRÉDITOS

- **Jonathan Archila**
- **Alura Latam**
- **Oracle Next Education**



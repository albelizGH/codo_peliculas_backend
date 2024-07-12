# Backend para AB-Movies

Este repositorio contiene el código del backend para AB-Movies, una aplicación web de gestión de películas y usuarios.

## Descripción del Proyecto

AB-Movies es una aplicación web desarrollada como proyecto para el curso Codo a Codo. Permite a los usuarios registrarse, iniciar sesión, gestionar su perfil y explorar información sobre películas.

El backend está desarrollado en Java utilizando JDBC y Tomcat, sin utilizar frameworks adicionales.

## Demostración

[![Video Demostración](https://github.com/user-attachments/assets/9c7c0a16-9bea-4dd9-a32b-a1451287c25b)](https://www.youtube.com/watch?v=PGc2zVXCcYQ)
https://www.youtube.com/watch?v=PGc2zVXCcYQ

## Funcionalidades

- **Registro de Usuarios:** Permite a los usuarios crear nuevas cuentas proporcionando nombre, apellido, email, contraseña, fecha de nacimiento y país.
- **Inicio de Sesión:** Autentica a los usuarios para acceder a sus perfiles y funcionalidades personalizadas.
- **Gestión de Perfiles:** Los usuarios pueden ver y actualizar sus datos personales.
- **Administración de Usuarios (Admin):** Funcionalidades para administradores como ver todos los usuarios registrados, eliminar usuarios y actualizar datos de usuarios.

## Tecnologías Utilizadas

- **Java**
- **JDBC** para la conexión con la base de datos MySQL.
- **Tomcat** como servidor web.
- **Servlets y JSP** para la lógica de control y las vistas dinámicas.

## Configuración

1. **Base de Datos:** Configura una base de datos MySQL llamada `movies-codo` con la estructura adecuada para almacenar la información de usuarios.
   
2. **Tomcat:** Configura Tomcat en tu entorno de desarrollo o servidor para desplegar el backend.

3. **Variables de Entorno:** Asegúrate de configurar las variables de entorno necesarias, como la URL de conexión a la base de datos y otros parámetros específicos.

## Instalación y Uso

1. Clona este repositorio:

   ```bash
   git clone https://github.com/tu-usuario/ab-movies-backend.git
   cd ab-movies-backend

2. Importa el proyecto en tu IDE Java preferido.

3. Configura las dependencias en el archivo pom.xml:
    
    ```bash
    <dependencies>
        <!-- Otras dependencias -->
        <dependency>
            <groupId>com.mysql</groupId>
            <artifactId>mysql-connector-j</artifactId>
            <version>9.0.0</version>
        </dependency>
        <dependency>
            <groupId>jakarta.servlet</groupId>
            <artifactId>jakarta.servlet-api</artifactId>
            <version>5.0.0</version>
        </dependency>
        <dependency>
            <groupId>com.fasterxml.jackson.core</groupId>
            <artifactId>jackson-databind</artifactId>
            <version>2.17.1</version>
        </dependency>
        <dependency>
            <groupId>com.fasterxml.jackson.datatype</groupId>
            <artifactId>jackson-datatype-jsr310</artifactId>
            <version>2.17.1</version>
        </dependency>
        <!-- Otras dependencias -->
    </dependencies>
    ```
    
4. Ejecuta la aplicación desde tu entorno de desarrollo o despliégala en tu servidor Tomcat.

## Autor
  Beliz Alejo






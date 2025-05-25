# CartMaster - Backend

Este es el backend de CartMaster, una aplicación para el registro y gestión de tarjetas de crédito.

## Requisitos Previos

- Java JDK 17
- Maven 3.x
- MySQL 8.x
- IDE (recomendado: IntelliJ IDEA o Spring Tool Suite)

## Tecnologías Utilizadas

- Spring Boot 3.5.0
- Spring Data JPA
- Spring Web
- MySQL Connector
- Lombok
- Spring DevTools

## Configuración del Proyecto

### Base de Datos
1. Crear una base de datos MySQL
2. Configurar las credenciales de la base de datos en `src/main/resources/application.properties`

### Clonar el Repositorio
```bash
git clone [https://github.com/AFlazaroo/CartMaster-BED.git]
cd CartMaster-BE
```

### Compilar el Proyecto
```bash
./mvnw clean install
```

### Ejecutar la Aplicación
```CartMasterApplication.java
```

La aplicación estará disponible en: `http://localhost:8080`

## Estructura del Proyecto

```
src/main/java/com/edu/cartmaster/
├── controller/     # Controladores REST
├── model/         # Entidades y modelos
├── repository/    # Repositorios JPA
├── service/       # Lógica de negocio
└── CartMasterApplication.java  # Clase principal
```

## Endpoints API

La documentación detallada de los endpoints estará disponible en:
- Swagger UI: `http://localhost:8080/swagger-ui.html`
- API Docs: `http://localhost:8080/v3/api-docs`

## Características

- Gestión de tarjetas de crédito
- Validación de datos
- Persistencia en base de datos MySQL
- API RESTful

## Desarrollo

Para desarrollo local:
1. Asegúrate de tener todas las dependencias instaladas
2. Configura tu IDE con Java 17
3. Importa el proyecto como proyecto Maven
4. Ejecuta la aplicación en modo desarrollo

## Construcción y Despliegue

Para construir el proyecto:
```bash
./mvnw clean package
```

## Configuración de Desarrollo

El proyecto utiliza las siguientes herramientas de desarrollo:
- Spring DevTools para recarga en caliente
- Lombok para reducción de código boilerplate
- Maven para gestión de dependencias y construcción

## Contacto

    aflazaro@unbosque.edu.co
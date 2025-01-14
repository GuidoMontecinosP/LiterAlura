# LiterAlura

Este es un proyecto de catálogo de libros desarrollado como parte del desafío LiterAlura. Permite realizar consultas a una API de libros, gestionar datos en una base de datos y realizar diferentes operaciones relacionadas con libros y autores.

## Funcionalidades

- **Buscar libro por título**: Consulta libros mediante un título proporcionado y muestra información relevante.
- **Listar libros registrados**: Obtén una lista de todos los libros guardados en la base de datos.
- **Listar autores registrados**: Visualiza todos los autores disponibles en la base de datos.
- **Filtrar autores vivos en un año específico**: Busca autores que estuvieron vivos durante un año proporcionado.
- **Filtrar libros por idioma**: Lista libros registrados en la base de datos según su idioma.

## Requisitos

- **Java**: JDK 17 o superior.
- **Maven**: Para gestionar las dependencias y compilar el proyecto.
- **PostgreSQL**: Base de datos para almacenar información de libros y autores.
- **API Gutendex**: Utilizada para obtener datos sobre libros.

## Configuración del Proyecto

1. Clona el repositorio:
   ```bash
   git clone https://github.com/GuidoMontecinosP/LiterAlura.git



Ve al directorio del proyecto:

```
cd LiterAlura
```
Configura las credenciales de tu base de datos en el archivo .env:

```

DB_HOST=localhost
DB_NAME=nombre_de_tu_base_de_datos
DB_USER=tu_usuario
DB_PASSWORD=tu_contraseña
```
Instala las dependencias con Maven:

```
mvn clean install
```
Ejecuta la aplicación:

```
mvn spring-boot:run
```
Estructura del Proyecto

```
LiterAlura/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com.challengeliteratura/
│   │   │       ├── client/
│   │   │       ├── entity/
│   │   │       ├── model/
│   │   │       ├── repository/
│   │   │       ├── service/
│   │   │       └── util/
│   │   └── resources/
│   └── test/
├── pom.xml
├── README.md
└── .env
```

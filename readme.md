# API de Gestión de Tópicos

## Descripción

Esta API permite gestionar tópicos con las siguientes funcionalidades:
- Registro de nuevos tópicos.
- Listado de todos los tópicos.
- Actualización de tópicos existentes.
- Eliminación de tópicos.
- Autenticación de usuarios.

## Endpoints
### Tópicos

#### `POST /topics`
- **Descripción**: Registra un nuevo tópico.
- **Parámetros**:
  - `title`: Título del tópico.
  - `description`: Descripción del tópico.

#### `GET /topics`
- **Descripción**: Lista todos los tópicos.

#### `PUT /topics/{id}`
- **Descripción**: Actualiza un tópico existente.
- **Parámetros**:
  - `id`: ID del tópico.
  - `title` (opcional): Nuevo título del tópico.
  - `description` (opcional): Nueva descripción del tópico.

#### `DELETE /topics/{id}`
- **Descripción**: Elimina un tópico existente.
- **Parámetros**:
  - `id`: ID del tópico.

## Requisitos

Para ejecutar este proyecto, necesitas:
- [Eclipse](https://www.eclipse.org/downloads/) actualizado.
- [Spring Framework](https://spring.io/tools) Plugin instalado en Eclipse.

## Instalación

1. **Descarga el archivo ZIP** del proyecto desde el repositorio.
2. **Actualiza Eclipse** a la última versión.
3. **Instala el plugin de Spring Framework**:
   - Abre Eclipse.
   - Ve a `Help -> Eclipse Marketplace`.
   - Busca "Spring Tools" e instálalo.
4. **Importa el proyecto**:
   - Abre Eclipse.
   - Ve a `File -> Import`.
   - Selecciona `Existing Projects into Workspace`.
   - Selecciona el archivo ZIP descargado y sigue los pasos para importar el proyecto.
5. **Extrae la carpeta `api`**:
   - Dentro de la carpeta `api` encontrarás un archivo .rar que contiene la API para pruebas.
   - Descomprime el archivo .rar para acceder a los archivos de la API.

## Uso

Una vez que hayas configurado el proyecto en Eclipse, puedes ejecutar la API y probar los endpoints utilizando herramientas como Postman o cURL.


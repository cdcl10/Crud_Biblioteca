# Crud_Biblioteca

## Descripción del Proyecto

El proyecto `Crud_Biblioteca` es una aplicación web desarrollada en ASP.NET MVC que permite gestionar una biblioteca de libros. Los usuarios pueden realizar operaciones de **Crear**, **Leer**, **Actualizar** y **Eliminar** libros y autores en una interfaz amigable. La aplicación utiliza una base de datos SQL para almacenar la información de manera eficiente.

## Características Principales

- **Gestión de Libros**: Agregar, editar y eliminar libros.
- **Gestión de Autores**: Selección de autores al agregar libros.
- **Interfaz Intuitiva**: Navegación fácil y accesible.
- **Base de Datos Relacional**: Implementa relaciones entre tablas para una correcta gestión de datos.

## Pasos para Configurar y Ejecutar la Aplicación

1. **Clonar el Repositorio**
   ```bash
   git clone https://github.com/tu_usuario/Crud_Biblioteca.git
   cd Crud_Biblioteca
Abrir el Proyecto en Visual Studio

Asegúrate de tener Visual Studio instalado. Abre el proyecto Crud_Biblioteca.sln en Visual Studio.
Configurar la Base de Datos

Asegúrate de tener SQL Server instalado y en funcionamiento.
Abre SQL Server Management Studio y crea una nueva base de datos llamada Crud_Biblioteca.
Ejecuta el script de la base de datos que se encuentra en el archivo script.sql dentro de la carpeta del proyecto para crear las tablas necesarias y las relaciones entre ellas.
Configurar la Cadena de Conexión

Abre el archivo Web.config y localiza la sección <connectionStrings>.
Modifica la cadena de conexión para que apunte a tu base de datos local, algo así:
xml
Copy code
<connectionStrings>
    <add name="DbModels" connectionString="Server=TU_SERVIDOR;Database=Crud_Biblioteca;Trusted_Connection=True;" providerName="System.Data.SqlClient" />
</connectionStrings>
Reemplaza TU_SERVIDOR con el nombre de tu instancia de SQL Server.
Compilar y Ejecutar la Aplicación

Presiona F5 o haz clic en "Iniciar" en Visual Studio para compilar y ejecutar la aplicación.
La aplicación se abrirá en tu navegador predeterminado, generalmente en http://localhost:xxxx, donde xxxx es el puerto asignado.
Interacción con la Aplicación

Puedes crear, editar y eliminar libros y autores utilizando la interfaz de usuario de la aplicación.
Navega a las diferentes secciones para explorar las funcionalidades.

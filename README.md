# Proyecto Tienda de Libros

Este proyecto, desarrollado con **Java 20**, es una aplicación de tienda de libros que permite gestionar el inventario y ventas de una librería. Utiliza **Java Swing** para la interfaz gráfica y **Spring Boot** para la lógica del backend. La información se almacena en una base de datos MySQL, la cual se crea automáticamente.

## Características

- **Agregar libros**: Permite a los usuarios añadir nuevos libros con información detallada.
- **Modificar libros**: Actualiza la información de libros existentes.
- **Listar libros**: Muestra todos los libros disponibles en la tienda.
- **Eliminar libros**: Remueve libros del inventario.

## Tecnologías Utilizadas

- **Java 20**
- **Java Swing**: Para la interfaz gráfica de usuario.
- **Spring Boot**: Para el backend y la gestión de la lógica de la aplicación.
- **Lombok**: Para reducir el código boilerplate en las clases Java.
- **MySQL**: Como sistema de gestión de bases de datos.

## Configuración de la Base de Datos

La configuración de la base de datos se encuentra en el archivo `application.properties`. Es necesario modificar los valores de `username` y `password` para que coincidan con los de tu entorno de MySQL.

```properties
#Conexion mysql
spring.datasource.url=jdbc:mysql://localhost:3306/tienda_libros_db?createDatabaseIfNotExist=true
spring.datasource.username=root
spring.datasource.password=123456
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
# Crea la base de datos en caso necesario
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

## Entornos de Desarrollo

El proyecto ha sido probado en los siguientes entornos:

- **IntelliJ IDEA**
- **NetBeans**
- **Eclipse**

## Uso

1. Clona el repositorio en tu máquina local.
2. Abre el proyecto en tu entorno de desarrollo preferido.
3. Ejecuta la aplicación desde la consola.

### Comandos de la Aplicación

- **Agregar contacto**: Permite añadir un nuevo contacto solicitando nombre, teléfono y email.
- **Modificar contacto**: Permite actualizar la información de un contacto existente.
- **Listar contactos**: Muestra todos los contactos guardados en la agenda.
- **Eliminar contacto**: Permite eliminar un contacto de la agenda.

## Contribuciones

Si deseas contribuir a este proyecto, por favor, sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una rama para tu nueva característica (`git checkout -b nueva-caracteristica`).
3. Realiza tus cambios y haz un commit (`git commit -m 'Añadir nueva característica'`).
4. Empuja tus cambios al repositorio (`git push origin nueva-caracteristica`).
5. Abre un Pull Request.


## Contacto

Para cualquier consulta o sugerencia, puedes contactar a [Diego Arriagada](mailto:tu-email@ejemplo.com).

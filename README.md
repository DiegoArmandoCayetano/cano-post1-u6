# 📦 MVC Productos - Gestión de Inventario Web

## 📄 Descripción del trabajo

Este proyecto corresponde al desarrollo de una aplicación web utilizando el patrón de arquitectura MVC (Modelo - Vista - Controlador) con Java, JSP y Servlets, como parte de la Unidad 6: JSP con MVC.

La aplicación permite gestionar un inventario de productos con operaciones básicas de creación, lectura, actualización y eliminación (CRUD), aplicando buenas prácticas de desarrollo web en Java.

---

## ⚙️ ¿Qué se hace en el proyecto?

La aplicación permite:

- Listar productos registrados en el sistema
- Agregar nuevos productos mediante un formulario
- Editar productos existentes
- Eliminar productos del sistema con confirmación
- Mostrar mensajes de confirmación en las operaciones
- Mantener la estructura MVC separando lógica, vista y control

---

## 🛠️ ¿Cómo se hizo?

El proyecto fue desarrollado utilizando:

- Java (Servlets y JSP)
- Patrón de arquitectura MVC
- JSTL para manejo de lógica en las vistas
- HTML para la estructura de las páginas
- Apache Tomcat como servidor de despliegue
- Maven para la gestión del proyecto

La lógica se separó en:
- **Modelo:** Clases que representan los datos (Producto)
- **Controlador:** Servlets que manejan la lógica de negocio
- **Vista:** JSP que muestran la información al usuario

Se implementó un flujo completo de navegación y manipulación de datos siguiendo el patrón MVC.

## Evidencias del Proyecto

### Ejecución en Tomcat
![Tomcat](docs/ejecucion_exitosa_Tomcat.PNG)

### Registrar nuevo producto
![Registrar producto](docs/registrar_nuevo_producto.PNG)

### Producto agregado
![Producto agregado](docs/producto_agregado.PNG)

### Editar producto
![Editar producto](docs/editar_producto.PNG)

### Confirmar eliminación
![Eliminar producto](docs/confirmar_eliminar_producto.PNG)

### Carga de productos precargados
![Carga productos](docs/carga_3_productos_precargados.PNG)


---

## 👨‍💻 Autor

- **Nombre:** Diego Armando Cayetano  
- **Proyecto:** mvc-productos  
- **Asignatura:** Programación Web - Unidad 6 (JSP con MVC)  
- **Año:** 2026

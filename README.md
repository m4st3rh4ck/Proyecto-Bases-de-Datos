# Proyecto-Bases-de-Datos
# Sistema de Ventas en Java con SQLite

Este proyecto es una **aplicación de escritorio** desarrollada en Java (Swing) que permite la gestión integral de un negocio, incluyendo clientes, proveedores, productos, ventas y usuarios. Usa SQLite como base de datos local, ideal para sistemas ligeros y portables sin necesidad de servidor externo.

Tecnologías utilizadas

- **Java (Swing):** Para la interfaz gráfica de usuario (GUI).
- **SQLite:** Base de datos embebida, sin necesidad de instalación adicional.
- **JDBC (sqlite-jdbc):** Driver que permite la conexión entre Java y SQLite.
- **NetBeans:** Entorno de desarrollo (IDE) usado para construir y ejecutar el proyecto.

Funcionalidades principales

- Gestión de clientes (CRUD).
- Registro y control de proveedores.
- Inventario de productos con stock y precios.
- Registro de ventas, historial y detalle por producto.
- Módulo de usuarios y autenticación de login.
- Configuración de datos de la empresa.
- Validaciones básicas en formularios.
- Interfaz amigable, con tablas y formularios dinámicos.

Estructura del sistema

El sistema está estructurado por capas:

- `Modelo`: Contiene las clases que representan las entidades (Cliente, Producto, Proveedor, etc.).
- `DAO`: Acceso a datos, implementado con JDBC y consultas SQL.
- `Vista`: Interfaz gráfica hecha con Java Swing.

Base de datos

- Archivo SQLite: `sistemaventa.db`
- Incluye tablas: `clientes`, `productos`, `proveedor`, `ventas`, `detalle`, `usuarios`, `config`.

No requiere servidor (como XAMPP o MySQL), lo que lo hace ideal para uso local o portable.

Cómo ejecutar el proyecto

0. Descombrime el archvio SV.rar
1. Abre el proyecto en NetBeans (Necesario tener Apache NetBeans instalado para poder abrirlo).
2. Asegúrate de tener el archivo `sqlite-jdbc.jar` en las librerías del proyecto.
3. Asegúrate de que el archivo `sistemaventa.db` esté en la carpeta `/src/database/`.
4. Ejecuta el archivo principal (generalmente `Sistema.java` o `login.java`).


## Autor

Gabriel Emanuel Hernández Espinoza  
Estudiante de Matemáticas Aplicadas y Computación, UNAM.

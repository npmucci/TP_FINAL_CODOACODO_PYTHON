# Complejo La Brava – API de Inventario y Reservas

## 📌 Introducción  
Aplicación desarrollada en **Python (Flask)** con **SQLite**, pensada para la **gestión de inventario** y el **manejo de reservas**.  
Incluye una **API RESTful** y una **interfaz web** con **HTML, CSS y JavaScript** para interactuar con el sistema de forma simple e intuitiva.  

⚠️ **Nota:** Este proyecto fue realizado como práctica. La versión en **PythonAnywhere** puede no estar disponible, pero la aplicación funciona en local.

---

## 🚀 Características  

- **API RESTful** con operaciones CRUD sobre productos.  
- **Carrito de reservas**, con actualización automática de inventario.  
- **Persistencia con SQLite**, creación de tablas automática.  
- **Interfaz Web dinámica** (JS) para altas, listados y reservas.  
- **CORS habilitado** para comunicación cliente-servidor.  

---

## ▶️ Endpoints principales  

- `GET /productos` → Lista todos los productos.  
- `GET /productos/<int:codigo>` → Consulta un producto específico.  
- `POST /productos` → Agrega un producto.  
- `PUT /productos/<int:codigo>` → Modifica un producto.  
- `DELETE /productos/<int:codigo>` → Elimina un producto.  
- `POST /carrito` → Agrega un producto al carrito.  
- `DELETE /carrito` → Elimina un producto del carrito.  
- `GET /carrito` → Muestra los productos del carrito.  

---

## 📖 Notas  
Este proyecto integra **backend (Flask + SQLite)** y **frontend ligero (HTML + CSS + JS)** para simular un sistema sencillo de inventario y reservas.  
Sirve como base para prácticas de desarrollo web y APIs REST.  

---

## 🔮 Próximos pasos  

- Implementar autenticación de usuarios.  
- Mejorar validaciones de datos en la API.  
- Desplegar nuevamente en un hosting activo.  

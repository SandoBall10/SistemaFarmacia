# 🧪 Sistema de Farmacia

Proyecto desarrollado por **Adrian Sandoval Ballona**

## 📋 Descripción

Este es un sistema de gestión para una farmacia, diseñado para facilitar el manejo de productos, inventario, ventas y clientes. El sistema permite registrar nuevos productos, actualizar su estado, llevar el control de ventas realizadas y gestionar los datos de los clientes de manera eficiente.

## 🚀 Tecnologías Utilizadas

- **Backend:** Java con Spring Boot  
- **Base de Datos:** H2 (en memoria) o JDBC  
- **Frontend:** HTML, CSS, JavaScript (según sea el caso)  
- **IDE:** IntelliJ IDEA / Visual Studio Code

## 📦 Funcionalidades Principales

- Registro de productos con nombre, precio, stock y categoría.
- Control de inventario en tiempo real.
- Gestión de clientes (registro, edición, eliminación).
- Procesamiento de ventas con cálculo de totales.
- Registro de detalles de cada venta (producto, cantidad, precio).
- Roles de usuario (Administrador, Vendedor).
  
## 🛠 Estructura del Proyecto

SistemaFarmacia-main/
raíz-del-proyecto/
│
├── farmacia-spring/         # Proyecto Backend - Spring Boot
│   ├── src/                # Código fuente Java
│   └── pom.xml             # Configuración de Maven
│
├── farmacia-app/           # Proyecto Frontend - React + Vite
│   ├── src/                # Código fuente TypeScript
│   ├── public/             # Archivos estáticos
│   └── package.json        # Configuración de dependencias

bash
Copiar
Editar

## 🔧 Instalación y Ejecución

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/tuusuario/SistemaFarmacia.git
Backend

Abrir con IntelliJ o cualquier IDE compatible.

Ejecutar SistemaFarmaciaApplication.java.

Asegurarse que el puerto definido (por defecto 8080) esté disponible.

Frontend

Abrir el archivo index.html en el navegador o levantar con un servidor local (como Live Server de VS Code).

📄 Base de Datos
El sistema puede usar H2 embebido o una conexión por JDBC. Se inicializa automáticamente con data.sql en el arranque de la aplicación.

🤝 Contribuciones
Las contribuciones son bienvenidas. Si deseas mejorar el proyecto, puedes hacer un fork y crear un Pull Request con tus cambios.

📧 Contacto
Adrian Sandoval Ballona
Correo: [sandovalballona@gmail.com]
GitHub: github.com/AdrianSB

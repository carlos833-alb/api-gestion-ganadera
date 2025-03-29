# 🛠️ API de Gestión Ganadera  
📌 **Backend desarrollado en Java Spring Boot con PostgreSQL**  

## 📜 **Descripción**  
Esta API permite la gestión de ganado bovino, incluyendo registro de animales, historial médico, reproducción y ventas.  

## 🚀 **Características**  
✅ **Registro de animales con identificación, raza y estado reproductivo**  
✅ **Historial médico con vacunas y tratamientos**  
<!--✅ **Gestión de ventas y facturación**  -->
<!--✅ **Control de usuarios con roles y permisos (Admin, Veterinario, Usuario)**  -->

## ⚙️ **Tecnologías Usadas**  
- **Lenguaje:** Java 23  
- **Framework:** Spring Boot  
<!-- - **Seguridad:** Spring Security + JWT  -->
- **Base de Datos:** PostgreSQL  
- **Herramientas:** Docker, Postman, Git  

## 🔑 **Ejemplo de Uso (Endpoints)**  
### 🔹 Obtener lista de animales  
```bash
GET /api/animales
Headers: Authorization: Bearer {token}

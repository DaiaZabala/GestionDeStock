
# 🧾 Sistema de Gestión de Stock

Proyecto para gestionar productos, stock y movimientos de inventario.  
Desarrollado con Node.js, Express, MySQL y Tailwind CSS.

---

## 🚀 Tecnologías utilizadas

- **Node.js** – Backend
- **Express.js** – Framework de servidor
- **MySQL** – Base de datos relacional
- **Tailwind CSS** – Estilos modernos y responsive
- **HTML + JavaScript** – Interfaz simple sin motores de plantillas

---

## 📁 Estructura del proyecto

```
/stock-app
│
├── /backend
│   ├── /routes
│   ├── /controllers
│   ├── /models
│   └── app.js
│
├── /frontend
│   ├── index.html
│   ├── main.js
│   └── estilos.css
```

---

## ⚙️ Instalación

1. Clonar el repositorio  
   `git clone https://github.com/tuusuario/stock-app.git`

2. Instalar dependencias del backend  
   ```bash
   cd backend
   npm install
   ```

3. Configurar base de datos MySQL  
   Crear una base llamada `stock_db` y una tabla `productos`.

4. Correr el servidor  
   ```bash
   node app.js
   ```

---

## 🛠 Funcionalidades principales

- [ ] Crear productos
- [ ] Listar productos
- [ ] Editar productos
- [ ] Eliminar productos
- [ ] Entradas / salidas de stock
- [ ] Usuarios con roles (futuro)

---

## 📌 Notas

- El frontend y el backend están completamente separados.
- La comunicación es a través de `fetch()` con peticiones HTTP.

---

## 💡 Pendientes

- Validaciones
- Autenticación
- Historial de movimientos

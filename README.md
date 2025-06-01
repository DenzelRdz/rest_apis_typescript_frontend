# 🛍️ Administrador de Productos

Aplicación web construida con **React** y **TypeScript**, diseñada para la gestión de productos. Ofrece funcionalidades como visualización de detalles de productos y formularios para su creación o edición. Desarrollada con **Vite** para un rendimiento óptimo y configurada para su despliegue en **Vercel**.

![FrontPage](https://github.com/user-attachments/assets/d9e07f05-25c2-4354-8bad-6d324cf59847)

---

## 🚀 Tecnologías utilizadas

- [React](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Vite](https://vitejs.dev/)
- [React Router](https://reactrouter.com/)
- [Vercel](https://vercel.com/)

---

## 📦 Instalación

Clona el repositorio e instala las dependencias:

```bash
git clone https://github.com/tuusuario/tu-repo.git
cd tu-repo
npm install
```

---

## 🧪 Ejecución en desarrollo

```bash
npm run dev
```

Accede a la app en `http://localhost:5173`.

---

## ⚙️ Scripts disponibles

- `npm run dev` – Ejecuta el servidor de desarrollo
- `npm run build` – Compila la app para producción
- `npm run preview` – Previsualiza la app en producción

---

## 🗂️ Estructura del proyecto

```
src/
├── components/        # Componentes reutilizables (ProductForm, ProductDetails, etc.)
├── layouts/           # Layout principal de la app
├── router.tsx         # Configuración de rutas
├── main.tsx           # Punto de entrada principal
├── index.css          # Estilos globales
```

---

## 📄 Despliegue

El proyecto incluye configuración para desplegarse en [Vercel](https://vercel.com/) mediante el archivo `vercel.json`.

---

## 🔐 Variables de entorno

Crea un archivo `.env.local` con las variables necesarias. Ejemplo:

```env
VITE_API_URL=https://tu-api.com
```

> Asegúrate de no subir este archivo al repositorio (está en `.gitignore`).

---

## 📝 Licencia

Este proyecto está bajo la licencia [MIT](LICENSE).

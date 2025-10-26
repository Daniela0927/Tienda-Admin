# tienda-admin-web

Interfaz web de administración (React + Vite) para la Tienda App.

## Configuración

- La aplicación asume que el backend está en `http://localhost:4000/api` por defecto.
- Para cambiarlo crea un archivo `.env` en la raíz con:
  ```
  VITE_API_BASE=https://tu-backend.com/api
  ```

## Ejecutar

```
npm install
npm run dev
```

## Funcionalidades

- Login admin (usa las credenciales creadas en el backend, por defecto admin@tienda.com / admin123).
- CRUD de productos (crear, editar, eliminar).
- Ver pedidos.

**# Aplicación Web de Gestión de Inventario**

Este repositorio contiene el proyecto de **Electiva Disciplinar II**, desarrollado por **Francisco Simón Sanmiguel Royo**, para la gestión básica de inventarios.
Este proyecto se está usando como punto de partida para la **actividad 4** del curso de **mantenimiento de software**.

**## Descripción**

La aplicación permite a los usuarios:

- Agregar nuevos productos con nombre, stock y precio.
- Visualizar la lista de productos registrados.

La aplicación está dividida en **frontend** y **backend**, comunicándose vía API REST.


**## Estructura del repositorio**

/frontend Código fuente del frontend desarrollado con React y Vite

/backend Código fuente del backend desarrollado con Node.js y Express


**## Ramas principales**

1. **caracteristica/agregar-producto** – Funcionalidad para agregar productos.  
2. **caracteristica/ver-productos** – Funcionalidad para visualizar productos.  
3. **caracteristica/integración** – Integración completa del frontend y backend.

---

**## Instalación y ejecución**

### Backend
1. Entrar a la carpeta `backend`.
2. Instalar dependencias:
   ```bash
   npm install

3. Ejecutar el servidor:

node server.js


4. El backend correrá en: http://localhost:3000



**Frontend**

**1.** Entrar a la carpeta frontend.

**2.** Instalar dependencias:

npm install

**3.** Ejecutar la aplicación:

npm run dev

**4.** Abrir en el navegador: http://localhost:5173



**Dependencias principales**

Frontend: ReactJS, Axios, React Router DOM

Backend: Node.js, Express, CORS


**Historias de usuario**

**1.** Agregar productos: Permitir al usuario registrar productos con nombre, stock y precio.


**2.** Visualizar productos: Mostrar al usuario la lista de productos registrados.


**3.** Integración completa: Asegurar que frontend y backend funcionen juntos correctamente.


**Capturas del proyecto**

Frontend:

Página de productos: Muestra la lista de productos y el formulario de agregar.

Backend:

Configuración inicial: Servidor corriendo y base de datos database.json creada.


**Autor**

Francisco Simón Sanmiguel. 

_Actividad realizada por cuenta propia, simulando un grupo colaborativo._

# Inventario Fullstack

Autor: Bertha46

Descripción
-----------
Proyecto de inventario fullstack. Contiene la aplicación (frontend y backend), la documentación mínima para instalar y ejecutar, y la planificación de la entrega.

Estado
------
- Estado actual: entrega preparada (revisar secciones de instalación y ejecutar pruebas).
- Recomendación: seguir pasos de instalación y ejecutar localmente para verificar dependencias.

Requisitos
---------
- Node.js >= 16 (si el backend/frontend usa Node)
- npm o yarn
- Python 3.x (si hay servicios Python)
- Docker (opcional, si se provee docker-compose)
- Git

Instalación (local)
-------------------
1. Clona tu repo (si aún no lo has hecho):
   - git clone https://github.com/Bertha46/inventario-fullstack-entrega.git
   - cd inventario-fullstack-entrega

2. Instala dependencias del backend (si existe package.json en la carpeta del backend):
   - cd backend || cd server
   - npm install

3. Instala dependencias del frontend (si existe package.json en la carpeta del frontend):
   - cd ../frontend || cd client
   - npm install

4. Variables de entorno:
   - Crea un archivo `.env` en la raíz del backend con las variables necesarias (ejemplo):
     ```
     PORT=3000
     DATABASE_URL=mongodb://localhost:27017/inventario
     JWT_SECRET=tu_secreto
     ```
   - Revisa la documentación del proyecto para variables específicas.

Ejecución
---------
- Backend:
  - Desde la carpeta del backend:
    - npm run dev   (o npm start)
- Frontend:
  - Desde la carpeta del frontend:
    - npm run dev   (o npm start)

Con Docker (si existe docker-compose.yml)
----------------------------------------
- docker-compose up --build

Pruebas
-------
- Si hay tests:
  - npm test
  - o revisa `package.json` para scripts de prueba.

Contribución y autoría
----------------------
Autor del repositorio y responsable de la entrega: Bertha46

Si vas a entregar este trabajo, asegúrate de:
- Actualizar la sección "Autor" y los datos de contacto si es necesario.
- Revisar que `docs/planificacion.txt` contenga la planificación solicitada por la materia.

Contacto
--------
- GitHub: https://github.com/Bertha46
- Email: (bmero4612@utm.edu.ec)

Licencia
--------
Añade aquí la licencia (ej. MIT) o elimina si no aplica.

Ecosoft_Project/
├── Ecosoft/                          
│   ├── backend/                      # Lógica backend con FastAPI
│   │   ├── main.py                   # Punto de entrada FastAPI
│   │   ├── database.py               # Configuración conexión BD
│   │   ├── .env                      # Variables de entorno
│   │   ├── .env.example              # Ejemplo de entorno
│   │   ├── requirements.txt          # Dependencias
│   │   │
│   │   ├── crud/                     # Operaciones CRUD por entidad
│   │   │   
│   │   │
│   │   ├── routes/                   # Endpoints organizados
│   │   │   ├── cliente.py
│   │   │   ├── domiciliario.py
│   │   │   ├── empleados.py
│   │   │   ├── factura.py
│   │   │   ├── inventario.py
│   │   │   ├── material.py
│   │   │   ├── pago_proveedor.py
│   │   │   ├── pedido.py
│   │   │   ├── proveedor.py
│   │   │   ├── __init__.py
│
│   ├── db/                           # Scripts y migraciones de BD
│   │   ├── init.sql
│
│   ├── frontend/                     # Proyecto frontend (Vite + React + Tailwind)
│   │   ├── index.html                # HTML principal
│   │   ├── package.json              # Configuración npm
│   │   ├── package-lock.json
│   │   ├── postcss.config.js         # Configuración PostCSS
│   │   ├── tailwind.config.js        # Configuración TailwindCSS
│   │   │
│   │   ├── src/                      # Código fuente del frontend
│   │   │   ├── App.jsx               # Componente raíz de la app
│   │   │   ├── index.css             # Estilos globales
│   │   │   ├── main.jsx              # Punto de entrada React
│   │   │   │
│   │   │   ├── components/           # Componentes reutilizables
│   │   │   │   ├── AdminPanel.jsx
│   │   │   │   ├── Header.jsx
│   │   │   │
│   │   │   ├── pages/                # Vistas/páginas principales
│   │   │   │   ├── Home.jsx
│   │   │   │   ├── Index.jsx
│   │   │   │   ├── Login.jsx
│   │   │   │   ├── Register.jsx
│
├── npm/                              # Dependencias npm (extra fuera del frontend)
├── package-lock.json                 # Lockfile npm


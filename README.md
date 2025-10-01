Ecosoft_Project/
├── Ecosoft/                   
│   ├── backend/               # Lógica principal de backend
│   │   ├── main.py            # Punto de entrada FastAPI
│   │   ├── database.py        # Configuración conexión a BD
│   │   ├── .env               # Variables de entorno
│   │   ├── .env.example       # Ejemplo de configuración de entorno
│   │   ├── requirements.txt   # Dependencias del backend
│   │   ├── crud/              # Operaciones CRUD por entidad
│   │   │   ├── cliente_crud.py
│   │   │   ├── domiciliario_crud.py
│   │   │   ├── empleados_crud.py
│   │   │   ├── factura_crud.py
│   │   │   ├── inventario_crud.py
│   │   │   ├── material_crud.py
│   │   │   ├── pago_proveedor_crud.py
│   │   │   ├── pedido_crud.py
│   │   │   ├── proveedor_crud.py
│   │   ├── routes/            # Rutas organizadas por recurso
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
│   │
│   ├── frontend/              # Carpeta del frontend (pendiente revisar)
│   ├── db/                    # Migraciones / definiciones de BD
│   ├── Ecosoft_Project/       # Posible duplicado o configs extra
│   └── npm                    # Dependencias Node.js
│
├── package-lock.json          # Lock de npm

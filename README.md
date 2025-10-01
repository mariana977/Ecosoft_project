# Ecosoft_project

reciclac-tech/ # carpeta raíz 
├─ backend/ # servidor Node/Express 
│ ├─ package.json 
│ ├─ .env # MYSQL connection, JWT secret 
│ └─ src/ 
│ ├─ index.js # servidor 
│ ├─ db.js # pool mysql 
│ ├─ routes/ 
│ │ ├─ auth.js # register/login 
│ │ └─ users.js # usuarios, roles, admin 
│ └─ middleware/ # auth middleware 
└─ frontend/ # React app (Vite) 
├─ package.json 
├─ tailwind.config.cjs 
├─ postcss.config.cjs 
└─ src/ 
├─ main.jsx 
├─ App.jsx 
├─ index-page.jsx # página index que habla de la empresa 
├─ pages/ 
│ ├─ Register.jsx 
│ ├─ Login.jsx 
│ └─ Home.jsx 
└─ components/ 
├─ Header.jsx 
├─ Footer.jsx 
└─ AdminPanel.jsx # panel para asignar roles 


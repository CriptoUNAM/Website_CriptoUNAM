# CriptoUNAM 🎓

Plataforma educativa descentralizada para aprender sobre blockchain, criptomonedas y Web3.

## 🚀 Características

- Cursos sobre blockchain y criptomonedas
- Integración con Web3 y wallets
- Sistema de certificaciones en blockchain
- Comunidad activa de estudiantes
- Eventos y workshops
- Modo oscuro/claro
- Diseño responsive

## 🛠️ Tecnologías

- React + TypeScript
- Ethers.js
- Web3
- React Router
- CSS Modules
- Vite

## 📋 Prerrequisitos

- Node.js (v16 o superior)
- npm o yarn
- MetaMask u otra wallet Web3
- Git

## 🔧 Instalación

1. Clonar el repositorio:
bash
git clone https://github.com/tu-usuario/criptounam.git
cd criptounam


2. Instalar dependencias:
bash
npm install
# o
yarn install


3. Crear archivo de variables de entorno: bash
cp .env.example .env



4. Configurar variables de entorno en el archivo `.env`:
env
VITE_APP_INFURA_ID=tu_infura_id
VITE_APP_CHAIN_ID=1
VITE_APP_NETWORK=mainnet


5. Iniciar el servidor de desarrollo:
ash
npm run dev
o
yarn dev


## 🏗️ Estructura del Proyecto
criptounam/
├── src/
│ ├── components/ # Componentes reutilizables
│ ├── context/ # Contextos de React (Wallet, Theme)
│ ├── pages/ # Páginas principales
│ ├── hooks/ # Custom hooks
│ ├── types/ # Tipos de TypeScript
│ ├── utils/ # Utilidades y helpers
│ ├── App.tsx # Componente principal
│ └── main.tsx # Punto de entrada
├── public/ # Archivos estáticos
└── vite.config.ts # Configuración de Vite


## 🔍 Scripts Disponibles
bash
Desarrollo
(npm run dev)         # Inicia servidor de desarrollo
Construcción
(npm run build)        # Construye para producción
(npm run preview)      # Vista previa de la build
Testing
(npm run test)         # Ejecuta tests
(npm run test:watch)   # Ejecuta tests en modo watch
Linting
( npm run lint)         # Ejecuta ESLint
(npm run lint:fix)     # Corrige errores de linting



## 🤝 Contribuir

1. Fork el proyecto
2. Crea tu rama de feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add: nueva característica'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

### 📝 Convenciones de Código

- Usar TypeScript para todo el código nuevo
- Seguir el estilo de código existente
- Documentar componentes y funciones complejas
- Escribir tests para nuevas características
- Usar nombres descriptivos para variables y funciones

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE.md](LICENSE.md) para detalles

## 👥 Equipo

- [Nombre del Desarrollador 1](https://github.com/usuario1) - Desarrollador Principal
- [Nombre del Desarrollador 2](https://github.com/usuario2) - UI/UX
- [Nombre del Desarrollador 3](https://github.com/usuario3) - Smart Contracts

## 📞 Contacto

- Website: [criptounam.com](https://criptounam.com)
- Email: contacto@criptounam.com
- Twitter: [@CriptoUNAM](https://twitter.com/Cripto_UNAM)
- Discord: [Servidor de CriptoUNAM](https://discord.gg/criptounam)

## 🙏 Agradecimientos

- UNAM por el apoyo institucional
- Comunidad de desarrolladores Web3
- Contribuidores y estudiantes

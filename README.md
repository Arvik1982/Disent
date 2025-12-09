# 🌍 Disent — Страны мира (React + TypeScript + Vite)

[![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-%23000000.svg?style=flat&logo=vite&logoColor=%2380FF)](https://vitejs.dev)
[![ReactRouter](https://img.shields.io/badge/React_Router-CA4245?style=flat&logo=react-router&logoColor=white)](https://reactrouter.com)

## 🎯 **Список стран с описанием**
**API**: [restcountries.com](https://restcountries.com/)  
**Функционал**:
- Список всех стран мира
- Детальная страница по клику (Name/Capital/Flag/Region/Population)
- Error handling (API ошибки)
- Responsive дизайн (module.css)

## ✅ **Статус: Полностью готово**
- ✅ Список стран (250+ стран)
- ✅ Детальная страница (Name/Flag/Capital/Region/Population)
- ✅ Error handling (API down/empty)
- ✅ TypeScript типизация
- ✅ React Router навигация
- ✅ Vite HMR (горячая перезагрузка)
- ✅ Responsive module.css

  
## 🚀 **Запуск**
- git clone https://github.com/Arvik1982/Disent.git
- cd Disent
- npm install
- npm run dev

src/
├── App.tsx # Root + Router
├── pages/
│ ├── Countries.tsx # Список стран
│ └── CountryDetails.tsx # Детальная страница
├── components/
│ ├── CountryCard.tsx # Карточка страны
│ └── ErrorBoundary.tsx # Обработка ошибок
├── hooks/
│ └── useCountries.ts # API + cache
├── types/
│ └── Country.ts # API типы
└── styles/
└── module.css # Responsive

## 📦 **Tech Stack**
{
"dependencies": {
"react": "^18.2.0",
"react-dom": "^18.2.0",
"react-router-dom": "^6.20.0",
"@types/react": "^18.2.0",
"@types/react-dom": "^18.2.0",
"typescript": "^5.2.0"
},
"devDependencies": {
"vite": "^5.0.0"
}
}


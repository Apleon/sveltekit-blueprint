<span align="center">

![Blueprint](https://raw.githubusercontent.com/a-sharapov/react-blueprint/master/public/icon-192x192.png)

# < Svektekit Blueprint 2022 />

![TypeScript](https://img.shields.io/badge/TypeScript-222?style=for-the-badge&logo=typescript&logoColor=f7df1e) ![SVELTE](https://img.shields.io/badge/SvelteKit-222?style=for-the-badge&logo=Svelte&logoColor=ff380d) ![Vitest](https://img.shields.io/badge/Vitest-222?style=for-the-badge&logo=vite&logoColor=3578e5) ![WorkBox](https://img.shields.io/badge/WorkBox-222?style=for-the-badge&logo=pwa&logoColor=85bded)

</span>
<span align="center">

![ESLINT](https://img.shields.io/badge/ESLint-555?style=flat-square&logo=eslint&logoColor=fff) ![Prettier](https://img.shields.io/badge/Prettier-555?style=flat-square&logo=prettier&logoColor=fff)

</span>

## 👆 Особенности

##### 🧊 Cборка включает в себя:
- TypeScript;
- ESLint и Prettier;
- Vite;
- VitePWA (WorkBox);

##### 🗺️ Топология проекта:
- *assets*: статические ресурсы, применяемые в компонентах
- *components*: переиспольюзуемые компоненты приложения
- *hooks*: вспомогательные функции для компонентов
- *stores*: микроменеджеры состояний
- *utils*: утилиты для работы с данными

### 🔌 Переменные окружения (.env)
````
Описаны в файле .env.example
````


### 📑 ESLint & Prettier
````
npm run lint
````
````
npm run format
````

## ⚙️ Запуск

### Docker 
✅ __(Рекомендуется)__

````
docker-compose up --build
````

### В вашей системе
⚠️ __(Не рекомендуется)__
````
npm run dev
````

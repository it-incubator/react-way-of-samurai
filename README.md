## Привет, самурай!
Мы обновили для тебя репозиторий по Пути Самурая 🥳

Конечно мир разработки не стабилен и изменчив, но сейчас, в 2025, этот репозиторий актуализирует знания полученные при просмотре [Курса "React JS - путь самурая 1.0"](https://www.youtube.com/playlist?list=PLcvhF2Wqh7DNVy1OCUpG3i5lyxyBWhGZ8)

Надеемся что будет полезно и интересно

---
# Создание React + TypeScript приложения на Vite
Пошаговая инструкция для быстрого старта проекта с Vite + React + TypeScript с использованием pnpm.

## 🚀 Создание проекта

Откройте терминал и выполните:
```pnpm create vite```

→ Введите:

* Имя проекта (например, ReactWayOfSamurai)
* Выберите React
* Выберите TypeScript

После этого перейдите в папку проекта:
```cd my-vite-app```

## 📦 Установка зависимостей
```pnpm install```

## 📦 Запуск проекта
```pnpm install```

## 📂 Структура проекта

❗️Обратите внимание на расположение файлов index.html, main.tsx и App.tsx - оно отличается от того что показывает Димыч в [06 - index.js, App, JSX](https://www.youtube.com/watch?v=CdweQ2F2qBI)

---
# Переход с CRA (npm) на Vite (pnpm)

Этот проект был перенесён с Create React App (CRA) + npm на Vite + pnpm.

Ниже — основные изменения и инструкции для работы.

## 📦 Установка зависимостей
Раньше использовался ***npm***, теперь — ***pnpm*** (быстрее и эффективнее).

### 1. Установка pnpm
Если у вас его нет, установите глобально:
```
npm install -g pnpm
// или (для Linux/macOS)
curl -fsSL https://get.pnpm.io/install.sh | sh -
```

### 2. Установка зависимостей
Вместо ```npm install``` теперь:
```pnpm install```
## 🚀 Запуск разработки
Раньше:
```npm start```

Теперь:
```pnpm dev```

→ Сервер запустится на http://localhost:5173 (а не 3000, как в CRA).

---

## 🔄 Что изменилось в коде?
### 1. Импорт React
Раньше нужно было явно импортировать React:

```import React from 'react';```

Теперь:

```
function App() { ... }  
// React 17+ — можно без импорта!
```
  
---
## 🔗 Полезные ссылки:
* [Vite Docs](https://vitejs.dev/)
* [PNPM Docs](https://pnpm.io/)
* [Миграция с CRA на Vite](https://vitest.dev/guide/migration.html)
* [TypeScript + React](https://vitejs.dev/)

---
Над проектом работали:

[Дарья Метелица](https://t.me/Dari_met)

[Елизавета Савинова](https://t.me/Veta_S0)

Нам будут приятны ваши респекты и отзывы 😉
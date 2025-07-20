# 🧪 Netology: Event Handling – Игра с гоблинами

[![Build status](https://ci.appveyor.com/api/projects/status/u58mddv1xq22xcdd?svg=true)](https://ci.appveyor.com/project/dm-morozov/netology-53-event-handling)
![CI](https://github.com/dm-morozov/Netology_53_event_handling/actions/workflows/web.yaml/badge.svg)
![Netology](https://img.shields.io/badge/TypeScript-JavaScript-blue)
🔗 [🚀 Github Pages (игра)](https://dm-morozov.github.io/Netology_53_event_handling/)

---

## 📘 Домашнее задание к занятию "3. Обработка событий"

### 📌 Правила сдачи задания:

* ✅ В рамках этого ДЗ **нужно использовать менеджер пакетов `yarn`**
  → Никакого `package-lock.json` в репозитории быть **не должно**
* ✅ Всё должно **собираться через Webpack**, включая:

  * изображения
  * стили
* ✅ Результат необходимо **выложить на GitHub Pages** с помощью **GitHub Actions**
  [Инструкция от Нетологии](./README_for_Netology.md)
* ✅ В `README.md`:

  * Бейджи CI
  * Ссылка на GitHub Pages

---

## 🎮 Игра с гоблинами

### 🧙 Легенда

Вы решили доделать игру с гоблинами, добавив оставшуюся игровую логику.

### 📋 Описание задачи

Нужно реализовать игру по следующим правилам:

* 🟢 Гоблин появляется в **рандомной ячейке** поля на **1 секунду**
* 🔨 Если пользователь успеет кликнуть по нему:

  * Засчитывается **+1 балл**
  * Гоблин исчезает
* 🔻 Если пользователь **не успеет**, считается **промах**

  * После **5 промахов** игра завершается
* 🖱️ **(опционально)** Реализуйте **кастомный курсор** в виде молотка
* 🧩 Код должен быть **структурирован через классы**

  * Каждый класс — за отдельную часть логики

---

## 🚀 Как запустить

```bash
git clone git@github.com:dm-morozov/Netology_53_event_handling.git
cd Netology_53_event_handling
yarn install
yarn start
```

### 🔧 Сборка:

```bash
yarn dev
yarn build
```

---

## 📂 Структура проекта

```
📁 src/
 ├── index.html          // Главная HTML-страница
 ├── index.ts            // Точка входа
 ├── ts/
 │   ├── Game.ts         // Логика игры
 │   └── ...             // Остальные модули
 ├── img/                // Изображения
 └── styles/             // Стили
```

---

## 💡 Чему научился

* Работа с DOM через события
* Реализация игровой логики
* Делегирование событий и взаимодействие с элементами
* Использование таймеров (`setInterval`)
* Настройка Webpack и CI/CD через GitHub Actions
* Публикация проекта на GitHub Pages

---

### 🌐 Демо:

Доступно по адресу:  
👉 [https://dm-morozov.github.io/Netology_53_event_handling/](https://dm-morozov.github.io/Netology_53_event_handling/)

---

## 📧 Контакты

Если возникнут вопросы, пишите:

* ![LinkedIn](./svg/linkedin-icon.svg) [LinkedIn](https://www.linkedin.com/in/dm-morozov/)
* ![Telegram](./svg/telegram.svg) [Telegram](https://t.me/dem2014)
* ![GitHub](./svg/github-icon.svg) [GitHub](https://github.com/dm-morozov/)

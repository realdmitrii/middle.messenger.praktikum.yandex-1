# Чат волчат sprint 4
![In process](https://img.shields.io/badge/status-production-brightgreen)
![Ya](https://img.shields.io/badge/yandex-practicum-yellow)
[![Netlify Status](https://api.netlify.com/api/v1/badges/78d7cf21-184d-45e4-9d3d-fc82f497226c/deploy-status)](https://app.netlify.com/sites/dapper-frangollo-6cdc5f/deploys)

## Описание
Учебный проект, в разработке
Польза: мессенджер для деловых людей с неудаляемыми сообщениями
Сайт: https://dapper-frangollo-6cdc5f.netlify.app/

## Установка
Проект открывается на 3000 порту, все команды в скриптах 
скрипт start - запуск


Дизайн-макет:
https://www.figma.com/file/jF5fFFzgGOxQeB4CmKWTiE/Chat_external_link?node-id=0%3A1


**Структура:**

- core: ключевые классы приложения и функции для работы с ними;
- pages: страницы;
- styles: стили.
- assets: изображения, svg иконки и шрифт;
- components: компоненты;
- data: данные о владельце, пользователях и выбранных чатах;
- pages: страницы;
- services: вспомогательные функции и классы;

**Реализация**  
На данный момент:

- регистрация, авторизация, выход из системы;
- создание чата, добавление и удаление пользователей из него;
- обмен сообщениями между пользователями посредством WebSocket;
- изменение данных владельца аккаунта, пароля к учётной записи а также аватара.

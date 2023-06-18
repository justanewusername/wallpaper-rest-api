# REST API бэкенд для андроид приложения [wallpaper](https://github.com/IlyaIIS/WallpaperGenerator)

## Как запустить
1) ``` npm install ```
2) Создать Базу данных в mysql и настроить соеденение в файле .env (файл .env с примером уже создан, там же можно поменять JWT ключ)
3) Выполните миграции: ```node migration.js up ```. Возможны некоторые проблемы с порядком их выполнения в этом случае необходимо прописать: ``` node migration.js run название_файла_миграции.js up ```
4) Запустите сервер: ``` npm start ```
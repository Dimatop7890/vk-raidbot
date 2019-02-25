# vk-raidbot

## Установка

0. Клонируем репозиторий
1. Ставим Node.js и npm
2. Заходим в директорию `bot`
3. Копируем файл `config.example.js` в `config.js` и редактируем под свои нужды
4. Устанавливаем зависимости с помощью `npm install`
5. При необходимости поднятия веб-сервера для ввода капчи собираем фронтенд
	1. Заходим в директорию `www` и собираем с помощью `npm install`, `npm run build`
	2. Если сервер запущен на ~~холокосте~~ локалхосте, проксируем локальный сервер, например, с помощью nginx
6. Снова заходим в директорию `bot` и запускаем бота командой `npm run start`

## Обновление

1. Обновляем репозиторий с помощью `git pull`
2. Переписываем конфиг, если он обновился, устанавливаем зависимости бота и фронтенда, пересобираем
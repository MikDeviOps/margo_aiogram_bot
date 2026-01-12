# margo_aiogram_bot

Создать .env файл в корне проекта:

Создать переменную: TOKEN = "Твой токен"


Сборка:

docker build -t my-bot .

Запуск:

docker run -d --name bot --env-file .env my-bot
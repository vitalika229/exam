# Exam Project

Этот проект включает простой сервер Express.js, упакованный в Docker.

## Запуск проекта

Для запуска проекта выполните следующие шаги:

1. Склонируйте репозиторий:

git clone https://github.com/vitalika229/exam.git

2. Перейдите в директорию проекта:

cd exam 

3. Соберите Docker образ:

docker build -t express-app .

4. Запустите контейнер:

docker run -p 3001:3000 -d express-app

После запуска сервера, перейдите по адресу http://localhost:3001 для проверки его работоспособности.

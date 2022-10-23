# yamdb_final
![Deploy badge](https://github.com/YuriyPukinskis/yamdb_final/actions/workflows/yamdb_workflow.yml/badge.svg)
## Описание
Continuous Integration и Continuous Deployment для ранее разработанного приложения
## Функционал
В рамках данной работы к ранее упакованному в контейнеры проекту yamdb добавлен следующий функционал:
    автоматический запуск тестов,
    обновление образов на Docker Hub,
    автоматический деплой на боевой сервер при пуше в главную ветку.
## Установка
Для запуска проекта на удаленном сервере необходимо:
    скопировать на сервер файлы docker-compose.yaml, .env и папку nginx
    создать переменные окружения в разделе secrets репозитория
## Документация к API доступна по адресу
http://51.250.87.52/redoc/
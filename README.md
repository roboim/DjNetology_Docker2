# Домашнее задание к лекции «Docker»

## Задание 2
Создайте контейнер для REST API сервера любого вашего проекта из курса по Django (например, CRUD: Склады и запасы).

##### Решение.
Необходимые файлы находятся в репозитории(docker файл и проект django).

Команды для создания образа и контейнера. Далее доступ через браузер по адресу 127.0.0.1:8000
```sh
docker build . --tag=dj1
docker run -p 8000:8000 --name=django1 dj1
```
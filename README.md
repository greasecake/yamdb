# YaMDB

## Описание
Проект **YaMDb** собирает отзывы пользователей на произведения Музыки, Кино и Литературы

![Django workflow](https://github.com/greasecake/yamdb_final/actions/workflows/yamdb_workflow.yml/badge.svg)

## Работа с приложением
### Запуск

После обновления кода в ветке **master**, проект автоматически проходит тесты и разворачивается на сервере

- **Админка:** http://chevu.co.vu/admin <br>
- **Документация Redoc:** http://chevu.co.vu/redoc <br>
- **Пример данных в API:** http://chevu.co.vu/api/v1/titles

## При запуске на собственном сервере
### Создать суперпользователя
<code>docker-compose exec web python manage.py createsuperuser</code>

### Заполнить базу тестовыми данными
<code>docker-compose exec web python manage.py loaddata fixtures.json</code>
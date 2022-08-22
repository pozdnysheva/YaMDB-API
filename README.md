# Проект YaMDb - сервис отзывов на произведения

### Авторы:
- [Позднышева Наталья](https://github.com/pozdnysheva "Github page")
- [Цеков Давид](https://github.com/TsekovDavid "Github page")

### Технологии:
- Python 3.7
- Django 2.2
- Django REST framework 3.12
- библиотека Simple JWT - работа с JWT-токеном

### С помощью этого проекта можно:
* Читать отзывы на произведения различных категорий и жанров
* Добавлять, изменять и удалять собственные отзывы
* Оставлять комментарии к отзывам

#### Документация доступна после запуска сервера по адресу:
```
http://localhost:8000/redoc/
```
### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/pozdnysheva/YaMDB-API.git
```

```
cd api_yamdb
```

Cоздать и активировать виртуальное окружение:

```
python -m venv venv
```

```
source venv/Scripts/activate
```

Установить зависимости из файла requirements.txt:

```
python -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Создать миграции:

```
python manage.py makemigrations reviews
```

Выполнить миграции:

```
python3 manage.py migrate
```

Заполнить базу данных тестовой информацией:

```
python manage.py load_to_database
```

Запустить проект:

```
python3 manage.py runserver
```

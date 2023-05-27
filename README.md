API Final Yatube
API Final Yatube - это RESTful API для социальной сети Yatube, предоставляющий возможности по работе с пользователями, постами и комментариями.

Установка
Склонируйте репозиторий на локальную машину:
git clone git@github.com:Tips95/api_yatube.git

Активируйте виртуальное окружение python -m venv venv

Установите зависимости pip install -r requirements.txt

Примените миграции: python manage.py migrate

Использование
API Final Yatube предоставляет следующие эндпоинты:

/api/v1/users/ - получение списка пользователей и создание нового пользователя

/api/v1/users/{id}/ - получение, обновление и удаление пользователя по его идентификатору

/api/v1/posts/ - получение списка постов и создание нового поста

/api/v1/posts/{id}/ - получение, обновление и удаление поста по его идентификатору

/api/v1/posts/{post_id}/comments/ - получение списка комментариев к посту и создание нового комментария

/api/v1/posts/{post_id}/comments/{comment_id}/- получение, обновление и удаление комментария к посту
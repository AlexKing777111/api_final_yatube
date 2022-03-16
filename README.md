## API  для проекта Yatube.
### Описание
Проект позволяет получать информацию о пользователях, их постах, группах, в которых они состоят и комментариях, которые они пишут.

### Запуск
Клонируйте репозиторий
```
    git clone git@github.com:AlexKing777111/yatube_project.git
```
Создайте и установите виртуальное окружение
```
    python -m venv venv
```
```
    source venv/Scripts/activate
```
Установите зависимости из файла requirements.txt
```
    pip install -r requirements.txt
```
Примените миграции
```
    python manage.py migrate
```

Запустите сервер
```
    python manage.py runserver
```
## Примеры запросов
Запрос информации о постах
```
    /api/v1/posts/
```
Запрос информации о конкретном посте
```
    /api/v1/posts/{id}/
```
Запрос комментариев к посту
```
    /api/v1/posts/{post_id}/comments/
```
Запрос информации о конкретном комментарии
```
    /api/v1/posts/{post_id}/comments/{id}/
```
Запрос информации о подписках пользователя
```
    /api/v1/follow/
```
### Автор
Александр Королев


#  store

## "Платформа для публикации платного контента"


Реализована платформа для публикации записей пользователей. Публикация может быть бесплатной, доступна любому пользователю без регистрации и платной, доступна только авторизованным пользователям, который оплатили разовую подписку. Для реализации оплаты подписки используется эквайринг [Stripe](https://stripe.com/docs/api). Регистрация пользователя по номеру телефона.

***
### Прежде чем начать использовать проект нужно:
* Установить на ПК пакет docker
* выставить настройки в config/settings.py

###
    LANGUAGE_CODE='ru-ru'
    TIME_ZONE='Europe/Novosibirsk'
    STRIPE_API_KEY=<STRIPE_API_KEY>
    POSTGRES_DB=
    POSTGRES_USER=
    POSTGRES_PASSWORD=
    DATABASES_HOST=db

***
### Запуск Docker проекта
docker-compose up -d --build


***
#### 
* будет добавлена учетная запись `+77777777777 12345` что бы войти c правами администратора


# Kittygram

**Kittygram** - социальная сеть для размещение фотографий домашних животных.
Проект, где пользователи могут регистрироваться, загружать фотографии кошек с описанием их достижений,
а также любоваться на других котов.

## Стэк технологий

- Python 3.9
- Django REST Framework 3.12.4
- Django 3.2
- Simplejwt 4.7.2
- djoser 2.1.0
- gunicorn==20.1.0
- nginx
- CI/CD GitHub Actions

## Как установить

1. Форкните и клонируйте проект в удобное место:\
   `cd нужное_место`\
   `git clone ссылка_на_git`
2. Создать файл .evn в корневой дериктории проекта:\
   `cp -n .env.expamle .env`\
   Описание переменных в .env.expamle: \
   `cat .env.expamle`
3. Указать в GitHub секреты Actions secrets:
   ```
   DOCKER_PASSWORD='Пароль от докер хаба'
   DOCKER_USERNAME='Пользователь докерхаба'
   HOST='адрес удаленного сервера'
   USER='пользователь на удаленном сервере'
   SSH_KEY='закрытый ключ доступа к серверу'
   SSH_PASSPHRASE='пароль от закрытого ключа'
   TELEGRAM_TO='ид учетки телеграмма'
   TELEGRAM_TOKEN='Токен бота'
   ```
4. Запушить для диплоя

## Об авторе

Андрей Тетнёв - ученик Яндекс.Практикума
[GitHub](https://github.com/AndrewDevMan/) | [E-mail](mailto:andreytetnev@yandex.ru)

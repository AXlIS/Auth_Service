#  Auth сервис 

Микросервис отвечает за авторизацию пользователя по API. 
Планируется работа в комплексе с разработанными ранее Админ панель, ETL и Async API Service.

## Основные компоненты системы

1. Авторизация через соц. сети (Mail, Yandex, VK)
2. Двухфакторная авторизация (TOTP)
3. ReCaptcha
4. Взаимодействие с FastAPI через Grpc для проверки роли пользователя
5. Rate limit

**Авторизация через соц сети**
[http://127.0.0.8/auth/api/v1/oauth/](http://127.0.0.8/auth/api/v1/oauth/)

**Двухфакторная авторизация**
[http://127.0.0.8/auth/api/v1/2fa/add](http://127.0.0.8/auth/api/v1/2fa/add)
[http://127.0.0.8/auth/api/v1/2fa/confirm](http://127.0.0.8/auth/api/v1/2fa/confirm)

**ReCaptcha**
[http://127.0.0.8/auth/api/v1/recaptcha](http://127.0.0.8/auth/api/v1/recaptcha)

## Используемые технологии
- Flask
- PostgreSQL
- Redis
- Docker
- Pytest
- SQLAlchemy
- Oauth

## Как развернуть и запустить проект

**Если установлена утилита для запуска Makefile**
```
make run_dev
```
 
 ## Краткое руководство использования
 
 после запуска доступен по [http://localhost:5000/swagger](http://localhost:5000/swagger)
 
 там даны все ручки и краткая инструкция к ним
 
 ## Тестирование проекта
 
**Если установлена утилита для запуска Makefile**

```
make api_tests
```

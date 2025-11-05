# Inertia + Django + Vite + React

## установка

### для работы проекта необходимы: 

- [UV](https://docs.astral.sh/uv/) 
- [npm](https://nodejs.org/)
****
- клонируем репозиторий
```
git clone git@github.com:marentsov/Django-InertiaJS-React.git
cd Django-InertiaJS-React
```
- устанавливаем проект
```
make install
make migrate
```
- создаем админа
```
make admin
```
Придумываем и вводим `Username`, `Email address` и `Password` админа

- открываем два терминала

- в первом:
```
make start-backend
```

- во втором:

```
make start-frontend
```
- переходим по ссылке http://localhost:8000/products/create

- добавляем товары через форму

- или переходим по ссылке http://localhost:8000/admin

- вводим `Username` и `Password` админа и добавляем товары 

- проект становится доступен по ссылке - http://localhost:8000/

## запуск через docker:
### для работы проекта необходимы: 

- [Docker](https://docs.docker.com/get-started/get-docker/)
****
- клонируем репозиторий
```
git clone git@github.com:marentsov/Django-InertiaJS-React.git
cd Django-InertiaJS-React
```
- запускаем проект
```
make docker-up
```
- выполняем миграции 
```
make docker-migrate
```
- создаем админа
```
make docker-admin
```
Придумываем и вводим `Username`, `Email address` и `Password` админа


- переходим по ссылке http://localhost:8000/products/create

- добавляем товары через форму

- или переходим по ссылке http://localhost:8000/admin

- вводим `Username` и `Password` админа и добавляем товары

- проект становится доступен по ссылке - http://localhost:8000/

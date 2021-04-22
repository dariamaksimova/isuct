### Установка Flask
    pip install Flask

### Установка SQLAlchemy
    pip install SQLAlchemy

### Docker
Устанавливаем на свой компьютер Docker

    docker run --name mybase -e POSTGRES_DB=mybase -e POSTGRES_USER=mybase -e POSTGRES_PASSWORD=mybase -p 5432:5432 -d postgres

### Установка миграций 

    flask db init
    flask db migrate
    flask db upgrade

### Запускаем проект

    flask run

После того как проект запустился, переходим в браузер и вводим в поисковой строке <b>127.0.0.1:5000</b>
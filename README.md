Установка Wordpress через Docker Compose.

Включает в себя: WordPress, Nginx, MySQL, Wp-cli

### Использование

Создайте файл `.env`, укажите в нём желаемые логины и пароли для базы данных.

Например: 
```
MYSQL_ROOT_PASSWORD=your_root_password
MYSQL_USER=your_wordpress_database_user
MYSQL_PASSWORD=your_wordpress_database_password
```

Запустить
```
docker-compose up -d
```

Подключиться к wp-cli
```
docker-compose run --rm cli bash
```

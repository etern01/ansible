Role Name
=========

Подготовка сервера для работы приложения на основе ОС Centos 7...!!!

Requirements
------------

ОС Centos 7

Role Variables
--------------

- SECRET_KEY_BASE - любая строка
- RAILS_ENV=production
- RAILS_LOG_TO_STDOUT=1
- DB_HOST - адрес хоста postgresql (127.0.0.1)
- DB_PORT - порт postgresql (5432)
- DB_NAME - имя базы данных
- DB_USER - пользователь в базе данных
- DB_PASSWORD - пароль для базы данных

Dependencies
------------

- geerlingguy.nginx
  version: 3.1.4
- community.postgresql
  verions: 2.2.0



License
-------

BSD


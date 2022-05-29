# test

Для того, чтобы иметь доступ к интерфейсу wordpress по адресу http://blog.example.com необходимо в файл /etc/hosts добавить строчку:

127.0.0.1 blog.example.com

для запуска всеи инфраструктуры необходимо:
- скопировать репозиторий на компьютре с установленным docker/docker-compose.
- перейти в /{директория копирования}/test
- заупстить команду "docker-compose up -d"


веб интерфейст wordpress доступен по адресу http://blog.example.com

веб интерфейст grafana - http://127.0.0.1:3000

login: admin
password: Xx123456

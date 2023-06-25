# module_e4_homework
Собран на docker образ Django (Linux, nginx, Django, Postgres, Gunicorn) сервера.
Задача решена с использованием Compose. В данном репозитории находится файл docker-compose.yml.
Запуск проекта: <code>docker-compose up -d</code>.
Данная команда создаёт контейнеры на основании compose-файла в текущей директории.
По адресу <code>http://localhost:8000/admin</code> доступна административная панель Django-проекта.
Логин и пароль административной панели прописаны заранее. Логин: <code>admin</code>, пароль: <code>admin</code>.
Ссылка на образ mpwsg/module_e4_homework-web в Docker Hub:
<a href="https://hub.docker.com/repository/docker/mpwsg/module_e4_homework-web/general">mpwsg/module_e4_homework-web</a>
Ссылка на образ mpwsg/module_e4_homework-nginx в Docker Hub:
<a href="https://hub.docker.com/repository/docker/mpwsg/module_e4_homework-nginx/general">mpwsg/module_e4_homework-nginx</a>

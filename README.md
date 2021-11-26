# Создаем docker images:
* docker build -t my_nginx .

# Пробрасываем каталог html в nginx:
* docker run -d --name my_nginx -p 80:80 -v /Users/ekaterina/Desktop/Docker/html:/usr/share/nginx/html nginx

# Переходим на localhost
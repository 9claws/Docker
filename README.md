команды для создания и запуска контейнера:

docker build --tag nginx

docker run -v /home/azat/Рабочий\ стол/docker/nginx:/usr/share/nginx/html -p 8080:80 -d nginx 

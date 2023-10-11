Образ:
docker build . --tag=my_hw

Запуск контейнера:
docker run -d -p 3737:80 my_hw

Проверка html:
curl localhost:3737
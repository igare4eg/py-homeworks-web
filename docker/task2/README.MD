Образ:

docker build . --tag=my_hw8

Запуск контейнера:

docker run -d -p 9874:3773 my_hw8

Проверка:

docker exec -it a14c442b76b8 /bin/sh

#curl localhost:3737
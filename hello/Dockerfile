FROM ubuntu:latest #версия образа
WORKDIR /usr/src/app #выбрал рабочую дирректорию
COPY . . #скопировал все файлы из текущей директории в директорию контейнера
RUN apt-get update && \
    apt-get install  -y g++ && \
    g++ -o hello hello_world.cpp
    #всё обновил
CMD ["./hello"] - #запустил hello

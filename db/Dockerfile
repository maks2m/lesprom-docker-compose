# Извлечение образа postgres 
FROM postgres:14-alpine
# Установка переменной часового пояса
#ENV TZ=Asia/Shanghai
# Установка часового пояса
#RUN ln -sf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone
# Импорт скрипта базы данных
COPY ./script.sql /docker-entrypoint-initdb.d
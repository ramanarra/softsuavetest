FROM postgres:13
MAINTAINER ram <ramakoteswara.venkateswarlu@softsuave.com>
ENV MYSQL_DATABASE test
ENV MYSQL_PASSWORD password  
WORKDIR /usr/src/app
ADD  . /docker-entrypoint-initdb.d
EXPOSE 3306

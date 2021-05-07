FROM postgres:13
MAINTAINER ram <ramakoteswara.venkateswarlu@softsuave.com>
ENV POSTGRES_DATABASE test
ENV POSTGRES_PASSWORD password  
WORKDIR /usr/src/app
ADD  . /docker-entrypoint-initdb.d
EXPOSE 3306

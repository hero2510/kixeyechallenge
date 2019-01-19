FROM redis

RUN apt-get -y update && \
    apt-get -y upgrade && \
    apt-get -y install wget

RUN wget https://raw.githubusercontent.com/Kixeye/testapp/master/resources/redis.conf -P /usr/local/etc/redis/

#CMD ["redis-server", "/usr/local/etc/redis/redis.conf"]
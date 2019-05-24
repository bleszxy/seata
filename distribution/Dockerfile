FROM adoptopenjdk/openjdk8:latest
MAINTAINER yaoshuai <ys@tsingj.com>

RUN mkdir -p /seata/bin
RUN mkdir -p /seata/conf
RUN mkdir -p /seata/lib

ADD bin/*.sh /seata/bin/
ADD conf/* /seata/conf/
ADD lib/* /seata/lib/

CMD ["/seata/bin/seata-server.sh"]
EXPOSE 8091
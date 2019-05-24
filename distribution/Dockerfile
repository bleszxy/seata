FROM jdk-8u191:20181213
MAINTAINER yaoshuai <ys@tsingj.com>

RUN mkdir /bin
RUN mkdir /conf
RUN mkdir /lib

ADD distribution/bin/*.sh /bin/
ADD distribution/conf/* /conf/
ADD distribution/lib/* /lib/

CMD ["/bin/seata-server.sh"]
EXPOSE 8091
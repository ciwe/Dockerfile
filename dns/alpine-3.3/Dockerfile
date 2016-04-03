FROM ciwe/base:alpine-3.3
MAINTAINER Lukasz Burylo <lukasz@burylo.com>

RUN apk --update add bind

VOLUME /etc/bind
CMD ["named","-c","/etc/bind/named.conf","-g","-u","named"]

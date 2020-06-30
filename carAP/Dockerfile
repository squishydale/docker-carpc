FROM alpine

MAINTAINER Jaka Hudoklin <offlinehacker@users.noreply.github.com>

RUN apk add --no-cache bash hostapd iw dnsmasq

ADD start.sh /start.sh

CMD /bin/sh /start.sh

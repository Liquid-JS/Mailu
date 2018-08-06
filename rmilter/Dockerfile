FROM interlegis/alpine-rmilter

COPY rmilter.conf /etc/rmilter.conf
COPY rsyslog.conf /etc/rsyslog.conf

COPY start.sh /start.sh

CMD ["/start.sh"]

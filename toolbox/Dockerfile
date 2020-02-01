FROM alpine
RUN apk add --no-cache curl wget busybox-extras netcat-openbsd python py-pip
RUN pip install awscli
RUN rm -rf /var/cache/apk/* && \  rm -rf /tmp/*
RUN apk --purge -v del pi-pip
CMD tail -f /dev/null

FROM alpine
RUN apk add --no-cache wget busybox-extras netcat-openbsd python py-pip
RUN pip install awscli
RUN apk --purge -v del py-pip
CMD tail -f /def/null

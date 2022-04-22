FROM alpine:latest
RUN  mkdir /app && mkdir /result && apk add --no-cache --upgrade bash
WORKDIR /app
COPY date.sh .
CMD /bin/sh -c /app/date.sh

FROM alpine:latest
RUN   mkdir /web_content && mkdir /web_config
WORKDIR /web_content
COPY index.php .
WORKDIR /web_config
COPY default.conf .
CMD sleep 200  

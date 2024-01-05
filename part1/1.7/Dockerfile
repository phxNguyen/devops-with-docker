FROM ubuntu:20.04

WORKDIR /usr/src/app

COPY simple-web.sh .

RUN apt update && \
    apt install -y curl && \
    chmod +x simple-web.sh

CMD ./simple-web.sh
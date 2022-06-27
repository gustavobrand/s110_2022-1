FROM alpine:latest

LABEL description="Atividade 01 do T2"

RUN apk add --update apache2
RUN rm -rf /var/cache/apk/*

EXPOSE 80/tcp
ENTRYPOINT ["httpd"]
CMD ["-D", "FOREGROUND"]
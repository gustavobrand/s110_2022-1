FROM alpine:latest
LABEL description="Servidor apache de teste"
RUN apk add --update apache2 python3
RUN rm -rf /var/cache/apk/*
EXPOSE 80/tcp
ENTRYPOINT ["httpd"]
CMD ["-D", "FOREGROUND"]
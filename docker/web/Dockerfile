FROM debian:latest
MAINTAINER iva@ivanikolova.eui

#EXPOSE 80

RUN apt-get update
RUN apt-get install -y apache2

CMD ["-D", "FOREGROUND"]
ENTRYPOINT ["apachectl"]


FROM radstudio/pa-radserver:latest

ARG dbhost
ARG dbport
ARG password=embtdocker

ENV PA_SERVER_PASSWORD=$password
ENV DB_HOST=$dbhost
ENV DB_PORT=$dbport

RUN service apache2 restart

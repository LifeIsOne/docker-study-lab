FROM openjdk:11-jdk-slim

WORKDIR /var/current/app

COPY ./entrypoint.sh ./entrypoint.sh

ENTRYPOINT ["/bin/bash", "entrypoint.sh"]
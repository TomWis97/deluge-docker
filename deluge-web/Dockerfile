FROM ubuntu:latest
RUN apt-get update && \
    apt-get install deluge-web -y
RUN useradd delugeuser -m
USER delugeuser
VOLUME ~/.config/deluge
EXPOSE 8112
CMD deluge-web

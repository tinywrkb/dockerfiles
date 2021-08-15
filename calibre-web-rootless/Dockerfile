FROM ghcr.io/linuxserver/calibre-web:latest

RUN \
  sed -i 's/attachment; //' /app/calibre-web/cps/helper.py

# add local files
COPY root/ /

# ports and volumes
EXPOSE 8083
VOLUME /config

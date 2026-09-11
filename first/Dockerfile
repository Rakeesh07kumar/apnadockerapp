FROM nginx:1.31.5-alpine3.24 AS motu
WORKDIR /remoteapp
LABEL developer="rakesh"
LABEL date="11 sep 26"
RUN echo "building appliaction: $APP_VERSION"
RUN echo "mera pahla docker file hai"


COPY index.html /usr/share/nginx/html/index.html

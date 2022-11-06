# Version: 0.0.1
FROM nginx:1.20-alpine 
LABEL maintainer: "daniel.hr.obretenov@gmail.com"
RUN apk add bash; apk update; apk add nginx
COPY index.html /usr/share/nginx/html
EXPOSE 80

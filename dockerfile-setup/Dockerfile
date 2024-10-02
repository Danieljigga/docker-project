FROM nginx:1.26.0-alpine

LABEL maintainer="JJTECH"

COPY src/html /usr/share/nginx/html

EXPOSE 80

CMD [ "nginx", "-g", "daemon off;" ]
FROM nginx:1.25.1-alpine

LABEL maintainer="anselme"

COPY src/html /usr/share/nginx/html

EXPOSE 80

CMD [ "nginx", "-g", "daemon off;" ]
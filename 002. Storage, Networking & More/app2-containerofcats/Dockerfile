FROM nginx:latest

LABEL maintainer="Animals4life"

COPY index.html /usr/share/nginx/html

COPY containerandcat*.jpg /usr/share/nginx/html

CMD ["nginx", "-g", "daemon off;"]

EXPOSE 80


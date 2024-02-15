FROM nginx:alpine

RUN rm -rf /usr/share/nginx/html/*

COPY . /usr/share/nginx/html

ENTRYPOINT ["/usr/share/nginx/html/entrypoint.sh"]

CMD ["nginx", "-g", "daemon off;"]


FROM nginx
RUN rm -rf /usr/share/nginx/html/*

COPY . usr/share/nginx/html

EXPOSE 80

ENTRYPOINT ["nginx"]
CMD ["-g", "daemon off;"]
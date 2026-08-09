FROM nginx:1.26-alpine
COPY --chown=nginx:nginx index.html /usr/share/nginx/html/index.html
COPY nginx.conf /etc/nginx/nginx.conf
USER nginx
EXPOSE 8080
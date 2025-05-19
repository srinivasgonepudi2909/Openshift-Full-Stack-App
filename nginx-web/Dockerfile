FROM nginx
RUN rm -f /usr/share/nginx/html/index.html \
        /etc/nginx/conf.d/default.conf \
        /etc/nginx/nginx.conf

COPY nginx.conf /etc/nginx/nginx.conf

COPY static/ /usr/share/nginx/html/


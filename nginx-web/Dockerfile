FROM nginx

# Remove default files
RUN rm -f /usr/share/nginx/html/index.html \
        /etc/nginx/conf.d/default.conf \
        /etc/nginx/nginx.conf

# Copy custom NGINX config
COPY nginx.conf /etc/nginx/nginx.conf

# Copy static content
COPY static/ /usr/share/nginx/html/


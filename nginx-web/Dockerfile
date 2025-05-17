FROM nginx

# Remove default files
RUN rm -f /usr/share/nginx/html/index.html
RUN rm -f /etc/nginx/conf.d/default.conf
RUN rm -f /etc/nginx/nginx.conf

# Copy custom NGINX config
COPY nginx.conf /etc/nginx/nginx.conf

# Copy static content
ADD static/ /usr/share/nginx/html/

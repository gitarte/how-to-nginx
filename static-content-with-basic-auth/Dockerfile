FROM nginx:latest
#config
RUN  mkdir -p   /var/www/schema
COPY nginx.conf /etc/nginx/nginx.conf
COPY htpasswd   /etc/nginx/htpasswd

#content
COPY index.html /var/www/index.html
COPY test.yml   /var/www/schema/test.yml
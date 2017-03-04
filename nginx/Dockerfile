# Get the NGINX Image from https://hub.docker.com/
FROM nginx:1.11.10

# Remove the default NGINX configurations
RUN rm -v /etc/nginx/nginx.conf

# Add our custom configuration file to replace the original one
ADD nginx.conf /etc/nginx/

RUN echo "daemon off;" >> /etc/nginx/nginx.conf

# "The EXPOSE instruction informs Docker that the container listens on the specified network ports at runtime"
# https://docs.docker.com/engine/reference/builder/#expose
EXPOSE 80

# Start NGINX
CMD service nginx start
Nginx Dockerfile
#
# https://github.com/dockerfile/nginx
#

# Pull base image.
FROM nginx:1.17.8-alpine

# Define working directory.
WORKDIR /etc/nginx

COPY nginx.conf /etc/nginx/conf.d/default.conf

# Define default command.
CMD ["nginx"]

# Expose ports.
EXPOSE 3000

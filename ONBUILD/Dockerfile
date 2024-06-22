# I am the author of this image
FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.htmi
ONBUILD COPY index.html /usr/share/nginx/html/index.htmi
CMD ["nginx","-g","daemon off;"]
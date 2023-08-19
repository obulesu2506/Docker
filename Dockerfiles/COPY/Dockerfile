FROM almalinux
RUN yum install -y nginx
RUN rm -rf /usr/share/nginx/html/index.html
COPY /home/ubuntu/Docker/Dockerfiles/COPY/qi /usr/share/nginx/html/
CMD ["nginx", "-g", "daemon off;"]

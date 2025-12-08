FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/index.html
LABEL author="dhanush"\
      company="elsevier"\
      topic="devops"
CMD ["nginx","-g","daemon off;"]

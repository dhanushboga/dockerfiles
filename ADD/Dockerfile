FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/dhanushboga/GIT/refs/heads/main/readme.MD /usr/share/nginx/html/index.html
RUN chmod +x /usr/share/nginx/html/index.html
ENV course="devops"\
    learner="dhanush"
LABEL author="kumar"\
      learner="dhanush"
CMD ["nginx","-g","daemon off;"]
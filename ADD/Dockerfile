FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf "/usr/share/nginx/html/index.html"
ADD "https://raw.githubusercontent.com/aikdp/pract-jenkins/refs/heads/main/readme.MD" "/usr/share/nginx/html/index.html"
RUN chmod +r "/usr/share/nginx/html/index.html"
ADD sample.rar /tmp/
CMD ["nginx", "-g", "daemon off;"]
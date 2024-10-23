FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/*
ADD https://github.com/kirantirumalasetty/terraform_aws_ec2/blob/main/readme.MD /usr/share/nginx/html/index.html
RUN chmod +xr /usr/share/nginx/html/index.html
ADD sample-1.tar /tmp/
CMD [ "nginx", "-g", "daemon off;" ]

# FROM    centos:7 
# RUN     yum install epel-release -y 
# RUN     yum install nginx -y  
# RUN     rm -rf /usr/share/nginx/html/* 
# COPY    index.html  /usr/share/nginx/html/index.html 
# ENV     COMPONENT=nginx 
# EXPOSE  80 
# LABEL   COMPONENT=${COMPONENT}
# CMD     ["nginx", "-g", "daemon off;"]  
# # CMD     nginx -g "daemon off;"

FROM        centos:7 
RUN         useradd roboshop   
USER        roboshop 
WORKDIR     /home/roboshop 
# CMD         ["google.com"] 
# ENTRYPOINT  [ "ping", "-c", "5" ]


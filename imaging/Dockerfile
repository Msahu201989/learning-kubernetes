FROM      centos:7
RUN       yum install epel-release -yum
RUN       yum install nginx -y
ENTRYPOINT ["nginx, "-g", "daemon off;"]
EXPOSE   80










##FROM     nginx
##RUN      echo Hello >/usr/share/nginx/html/index.html
#
#FROM     centos:7
#RUN      yum install epel-release -y
#RUN      yum install nginx -y
#ENTRYPOINT ["nginx", "-g", "daemon off;"]
#EXPOSE    80
###
##
#FROM centos:7
#ENTRYPOINT ["ping", "-c3"]
#CMD ["google.com"]
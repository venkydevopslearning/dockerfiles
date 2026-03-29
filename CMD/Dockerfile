FROM redhat/ubi9
RUN  yum install nginx -y
CMD  ["nginx","-g","daemon off;"] 
# When the container starts, run nginx web server and keep it running in the foreground so the container stays alive.
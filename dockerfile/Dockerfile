FROM httpd:latest

RUN apt update
RUN apt install -y emacs -y apache2 -y apache2-utils iproute2 iputils-ping dnsutils
COPY index.html /usr/share/apache2/htdocs/

CMD ["httpd-foreground"]
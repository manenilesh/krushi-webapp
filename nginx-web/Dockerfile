FROM ubuntu

RUN apt update

RUN apt install -y nginx

COPY ./default /etc/nginx/sites-available/default

RUN ln -sf /etc/nginx/sites-available/default /etc/nginx/sites-enabled/default

RUN rm -f /etc/nginx/sites-enabled/default.conf || true

RUN nginx

EXPOSE 80


#CMD [ "nginx", "-g", "daemon off;" ]


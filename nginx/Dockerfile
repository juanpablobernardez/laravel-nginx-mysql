FROM nginx

COPY ./conf/backend.conf /etc/nginx/conf.d/backend.conf
#COPY ./conf/frontend.conf /etc/nginx/conf.d/frontend.conf

#RUN mkdir /etc/nginx/sites-enabled

#RUN ln -s /etc/nginx/sites-available/backend /etc/nginx/sites-enabled/backend
#RUN ln -s /etc/nginx/sites-available/frontend /etc/nginx/sites-enabled/frontend

RUN /etc/init.d/nginx restart

RUN apt update && apt install -y nano



FROM nginx


RUN rm /etc/nginx/conf.d/default.conf
COPY bhp.conf /etc/nginx/conf.d/
WORKDIR /usr/src/app
COPY . /usr/src/app


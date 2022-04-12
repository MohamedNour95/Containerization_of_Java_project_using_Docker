FROM nginx
#remove the default config of nginx
RUN rm -rf etc/nginx/conf.d/*
#add new nginx config
COPY ./nginx.conf /etc/nginx/conf.d/vproapp.conf



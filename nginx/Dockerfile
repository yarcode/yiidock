FROM nginx:alpine

ADD config/nginx.conf    /etc/nginx/
ADD config/app-frontend.conf /etc/nginx/conf.d/
ADD config/app-backend.conf /etc/nginx/conf.d/

EXPOSE 8001 8002

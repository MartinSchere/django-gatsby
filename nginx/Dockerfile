FROM nginxinc/nginx-unprivileged 

USER root

RUN mkdir -p /nginx_proxy_cache
RUN rm /etc/nginx/conf.d/default.conf

COPY ./default.conf /etc/nginx/conf.d

USER nginx

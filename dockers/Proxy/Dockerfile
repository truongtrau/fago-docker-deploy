FROM thuandv7/iot-gateway-nginx

RUN rm -f /etc/nginx/nginx.conf

COPY dockers/Proxy/nginx.conf /etc/nginx/nginx.conf
ADD dockers/Proxy/ssl /etc/nginx/ssl

EXPOSE 5000 5443
CMD ["nginx", "-g", "daemon off;"]
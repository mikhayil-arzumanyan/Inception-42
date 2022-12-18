FROM debian:buster
WORKDIR /tmp/nginx/
COPY .
RUN chmod +x install.sh && ./instal.sh && rm install.sh
CMD ["nginx", "-g", "deamon off;"]

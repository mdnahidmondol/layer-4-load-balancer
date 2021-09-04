FROM nginx
RUN apt update
RUN apt install dnsutils -y
RUN apt install -y net-tools
RUN apt intall telnet -y
COPY ./index.html /usr/share/nginx/html/index.html

CMD [ "nginx", "-g", "daemon off;" ]
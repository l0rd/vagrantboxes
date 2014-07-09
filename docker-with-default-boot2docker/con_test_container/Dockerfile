FROM ubuntu:12.04
RUN apt-get update
RUN apt-get install -y curl
CMD while true; do curl -s http://$APACHE_PORT_80_TCP_ADDR:80/; sleep 5; done


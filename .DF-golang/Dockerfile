FROM debian:10

RUN apt-get update 
RUN apt install wget -y
RUN apt install nano -y

RUN echo "testeeeeee"

RUN wget https://go.dev/dl/go1.18.2.linux-amd64.tar.gz
RUN tar -xzvf go1.18.2.linux-amd64.tar.gz
RUN mv go /usr/local/

COPY READ-ME.txt /

ENTRYPOINT [ "bash" ]


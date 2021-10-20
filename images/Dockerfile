FROM ubuntu

RUN apt-get update

RUN echo y | apt install python3.8

RUN echo y | apt install git

RUN git clone https://github.com/Jslsn/testing.git

ENTRYPOINT ["./testing/msg/"]

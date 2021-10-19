FROM ubuntu

RUN apt-get update

RUN echo y | apt install python3.8

RUN apt install git-all

RUN git clone https://github.com/Jslsn/testing.git

RUN cd testing/msg/

RUN step.py

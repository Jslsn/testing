FROM ubuntu

RUN apt-get update

RUN echo y | apt install python3.8

RUN echo y | apt install git

RUN git clone https://github.com/Jslsn/testing.git

RUN cd testing/msg ; python3.8 step.py

RUN python3.8 step.py

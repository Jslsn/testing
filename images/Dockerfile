FROM ubuntu

RUN apt-get update

RUN echo y | apt install python3.8

RUN echo y | apt install git

RUN git clone https://github.com/Jslsn/testing.git

ENTRYPOINT ["python3.8", "-u","./testing/msg/stage2.py"]

FROM ubuntu

RUN apt-get update && apt-get install -y locales && rm -rf /var/lib/apt/lists/* \ && localedef -i en_US -c -f UTF-8 -A /usr/share/locale/locale.alias en_US.UTF-8

RUN apt 

ENV LANG en_US.utf8

RUN apt install python3.8

RUN apt install git-all

RUN git clone https://github.com/Jslsn/testing.git

RUN cd testing/msg/

RUN step.py

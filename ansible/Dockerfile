FROM ubuntu:22.04

RUN apt-get update
RUN apt-get install python3.9 python3-pip -y

RUN pip install ansible

RUN apt-get install sshpass -y

RUN mkdir -p ./src
WORKDIR ./src

COPY ./src .

CMD ./cmd.sh
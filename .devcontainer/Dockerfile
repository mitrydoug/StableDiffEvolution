FROM ubuntu:24.04

RUN apt update

# install git
RUN apt install -y git

# install Python 3.11
RUN apt install -y software-properties-common
RUN add-apt-repository ppa:deadsnakes/ppa
RUN apt update
RUN apt install -y python3.10 python3.10-venv
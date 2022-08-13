FROM ubuntu:18.04
RUN yes | unminimize
RUN apt-get update && apt-get install -y \
	cmake \
	curl \
	git \
	nano \
	unzip \
	vim \
	wget \
	strace

RUN useradd lab -s /bin/bash -U -m
USER lab
WORKDIR /home/lab

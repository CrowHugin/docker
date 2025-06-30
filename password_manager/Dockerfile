# syntax=docker/dockerfile:1

FROM ubuntu:22.04
RUN apt-get update && apt-get upgrade -y
RUN apt install python3 -y && apt install python3-pip -y

COPY /home/bastien/Documents/prog/python/password-manager/ ./usr/local/etc/
RUN cd "./usr/local/etc"
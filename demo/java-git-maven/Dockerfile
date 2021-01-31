ARG ubuntuTag=20.04

FROM ubuntu:${ubuntuTag}

LABEL maintainer="Richard Fichtner" description="Image with java11, git and maven for demos. Do not use in production!"

RUN apt update && apt upgrade -y
RUN apt install openjdk-11-jre-headless -y
RUN apt install git -y
RUN apt install maven -y 


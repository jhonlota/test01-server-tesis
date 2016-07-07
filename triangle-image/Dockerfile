FROM ubuntu:14.04
RUN mkdir /triangle
COPY ./triangle /triangle
WORKDIR /triangle
RUN apt-get update -y 
RUN apt-get upgrade -y
RUN apt-get install -y zip gzip tar make gcc libx11-dev wget
RUN make all
RUN wget https://www.cs.cmu.edu/~quake/box.1.node

FROM maven:3-openjdk-11

LABEL maintainer="Jocenildo Paraizo <baianux@gmail.com>"

RUN apt-get -y update; apt-get -y install wget python build-essential git libfontconfig curl rsync
RUN wget -qO- https://deb.nodesource.com/setup_12.x > node_setup.sh
RUN bash node_setup.sh
RUN apt-get -y install nodejs
RUN npm install -g npm

CMD /bin/bash 

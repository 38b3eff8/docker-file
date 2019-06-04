FROM ubuntu-latest

RUN apt-get update && apt-get upgrade -y && apt-get install -y wget

RUN wget https://nodejs.org/dist/v6.2.0/node-v6.2.0-linux-x64.tar.gz

RUN tar -zxvf node-v6.2.0-linux-x64.tar.gz && mv node-v6.2.0-linux-x64 /usr/local/share/node

ENV NODE_HOME /usr/local/share/node
ENV PATH $PATH:$NODE_HOME/bin
ENV NODE_PATH $NODE_HOME/lib/node_modules

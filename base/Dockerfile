FROM ubuntu:14.04

RUN apt-get update -y && \
    apt-get upgrade -y && \
    apt-get install -y curl

# install nodejs + npm.  (source: https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-an-ubuntu-14-04-server)
RUN curl -sL https://rpm.nodesource.com/setup_5.x | bash -

RUN apt-get update -y && \
    apt-get install -y nodejs build-essential libssl-dev

EXPOSE 9080

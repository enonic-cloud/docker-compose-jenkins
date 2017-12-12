FROM jenkins:2.60.3

# Installing docker
USER root

RUN curl -L https://github.com/docker/compose/releases/download/1.5.2/docker-compose-`uname -s`-`uname -m` > /usr/local/bin/docker-compose
RUN curl -L https://get.docker.com/builds/Linux/x86_64/docker-1.8.3.tgz | tar -xz -C /
#RUN mv /tmp/docker/* /usr/local/bin/.
RUN chmod +x /usr/local/bin/docker*

RUN apt-get update
RUN apt-get install -y nodejs

USER jenkins

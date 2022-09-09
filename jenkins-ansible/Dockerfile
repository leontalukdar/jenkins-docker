FROM jenkins/jenkins:lts

USER root

RUN apt-get update && \
    apt-get install -y iputils-ping && \
    apt-get install -y python3-pip && \
    pip install ansible --upgrade

USER jenkins
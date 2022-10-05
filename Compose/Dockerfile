FROM gcr.io/educative-exec-env/educative-ubuntu-microvm:latest
RUN apt-get update && apt-get install -y curl wget
RUN wget -qO- https://get.docker.com/ | sh 
RUN curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose && chmod +x /usr/local/bin/docker-compose && ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
COPY dockercomposephp .
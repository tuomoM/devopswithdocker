FROM ubuntu:latest
RUN apt update && apt-get install -y git && apt-get install -y nodejs && apt-get install -y npm && apt-get install -y xsel
WORKDIR /node/app/

RUN git clone https://github.com/docker-hy/backend-example-docker.git .
RUN npm install


ENTRYPOINT npm start
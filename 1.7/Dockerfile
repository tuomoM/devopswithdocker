FROM ubuntu:16.04
RUN apt-get update && apt-get install -y wget
RUN apt-get install -y curl 
WORKDIR /mydir
COPY script.sh .
RUN chmod +rx ./script.sh
ENTRYPOINT [ "./script.sh" ]


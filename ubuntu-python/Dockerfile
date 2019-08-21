FROM ubuntu:18.04

RUN apt update && \
    apt install -y python3

EXPOSE 8888

CMD [ "python3",  "-m", "http.server", "8888" ]
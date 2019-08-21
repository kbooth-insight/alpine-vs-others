FROM golang:stretch

RUN apt update && \
    apt install -y git && \
    go get -u github.com/rakyll/hey && \
    apt remove -y git && \
    rm -rf /var/lib/apt/lists/*



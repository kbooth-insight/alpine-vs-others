FROM alpine:3.10

RUN apk update  && \
    apk add python3

EXPOSE 8000

CMD [ "python3",  "-m", "http.server" ]
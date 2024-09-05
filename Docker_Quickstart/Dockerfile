FROM python:3.8-slim

ARG DEV_MODE=0

ENV SOME_ENV='value of some environment variable'\
    OTHER_ENV='something'

RUN apt-get update -y && apt-get install -y vim 

COPY ./somefile.txt /

WORKDIR /

CMD ["/bin/bash"]



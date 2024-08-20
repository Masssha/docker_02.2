FROM ubuntu:latest
LABEL authors="massh"
COPY . .
RUN pip3 install requirements.txt
ENV MY_ENV=hello
EXPOSE 5050

ENTRYPOINT ["top", "-b"]
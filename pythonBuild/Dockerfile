FROM ubuntu:latest
MAINTAINER mokrish
RUN apt-get update
RUN apt-get install python -y
COPY test.py /var/test.py
EXPOSE 8080 8081
CMD python /var/test.py 

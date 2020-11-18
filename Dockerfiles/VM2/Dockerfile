FROM ubuntu:latest


RUN apt-get update
RUN apt-get install -y default-jre
RUN apt-get install -y default-jdk
RUN apt-get install -y python3

ADD consumer.py ~/consumer.py
 

CMD ["~/consumer.py"]

ENTRYPOINT ["python3"]

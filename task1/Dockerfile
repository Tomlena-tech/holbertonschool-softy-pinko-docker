  FROM ubuntu:latest

  RUN apt-get update

  RUN apt-get upgrade -y

  RUN apt-get install -y python3 python3-pip

  RUN flask pip3 

  WORKDIR /app

  COPY ./api.py /app/api.py



  CMD ["python3", "--version"]

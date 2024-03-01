FROM ubuntu

WORKDIR /mydemo

COPY . /mydemo/
RUN apt-get update && apt-get install -y python3-pip
CMD ["python","App.py"]
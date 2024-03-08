FROM "ubuntu"

WORKDIR /myApp
COPY . /myApp/

RUN apt-get update && apt get install python3 python3-pip

CMD ["python3","App.py"]
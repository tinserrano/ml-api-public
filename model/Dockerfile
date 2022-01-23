FROM python:3.8.5

ADD requirements.txt .
RUN pip3 install -r requirements.txt

ADD ./ /src/

WORKDIR /src

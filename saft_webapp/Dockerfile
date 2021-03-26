FROM python:3.7.6

ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

RUN mkdir /saft_webapp

WORKDIR /saft_webapp

COPY . /saft_webapp/

RUN pip install -r requirements.txt

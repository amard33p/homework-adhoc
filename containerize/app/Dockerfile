FROM python:3.8-alpine

WORKDIR /usr/src/app

# set environment variables
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

# install dependencies
COPY ./src/requirements.txt /usr/src/app/requirements.txt
RUN pip install --upgrade pip && pip install -r requirements.txt


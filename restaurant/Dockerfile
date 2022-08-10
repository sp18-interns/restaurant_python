# syntax = docker/dockerfile

FROM python:3.9-alpine3.13
ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1

WORKDIR /auth
COPY requirements.txt /auth/
RUN apk update
RUN apk add postgresql-dev gcc python3-dev musl-dev
RUN pip install -r requirements.txt
COPY . /auth/
FROM python:3.13-slim

WORKDIR /workspace
COPY . /workspace

RUN apt-get update && apt-get install -y git curl && \
    pip install --upgrade pip

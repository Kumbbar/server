FROM python:3.12-slim

WORKDIR /tests

COPY requirements.txt requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

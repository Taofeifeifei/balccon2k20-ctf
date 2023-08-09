FROM python:3.12.0b4

RUN pip install flask

COPY app/ /app/

WORKDIR /app

ENV READONLY 1

CMD python /app/app.py

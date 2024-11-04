FROM python:3.14.0a1

RUN pip install flask

COPY app/ /app/

WORKDIR /app

ENV READONLY 1

CMD python /app/app.py

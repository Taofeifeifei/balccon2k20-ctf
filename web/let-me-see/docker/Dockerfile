FROM python:3.12.0b1

RUN pip install flask

COPY bin/ /usr/local/bin/

COPY lib/ /usr/local/lib/

ENV LD_LIBRARY_PATH=/usr/local/lib/

COPY app/ /app/

COPY flag.txt /

CMD python /app/app.py

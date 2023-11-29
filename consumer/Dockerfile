FROM python:3.13.0a2-slim

ENV PYTHONDONTWRITEBYTECODE=1

RUN pip3 install kafka-python

COPY consumer .


CMD ["python3", "-u", "./consumer.py"]
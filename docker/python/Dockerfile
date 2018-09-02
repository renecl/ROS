FROM python:latest

RUN apt-get update \
    && apt-get install -y cron \
    && apt-get autoremove -y

ADD . /code
WORKDIR /code
RUN pip install -r requirements.txt
CMD ["python", "downloadmaker.py"]


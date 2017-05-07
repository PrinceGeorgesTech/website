FROM python:3
ENV PYTHONUNBUFFERED 1
RUN mkdir -p /home/vcap/app
WORKDIR /home/vcap/app
ADD requirements.txt /home/vcap/app
RUN pip install -r requirements.txt
ADD . /home/vcap/app

FROM python:2.7.13
ADD ./DS1307.py /snippet.py

RUN apt-get update
RUN apt-get install libffi-dev -y
RUN apt-get install libssl-dev -y
RUN apt-get install python-dev -y
RUN pip install smbus-cffi

CMD ["python", "/snippet.py"]
 

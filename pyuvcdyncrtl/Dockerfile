FROM python:2.7.13
ADD ./pyuvcdyncrtl.py /snippet.py

RUN apt-get update
RUN apt-get install python-gtk2-dev -y

CMD ["python", "/snippet.py"]


FROM python:2.7.13
ADD lookup.py /snippet.py

RUN pip install gdata
RUN pip install dataset
RUN pip install lxml
RUN pip install requests

CMD ["python", "/snippet.py"]


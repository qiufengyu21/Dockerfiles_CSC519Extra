FROM python:2.7.13
# Copy all the python files
ADD ./sensortag2xively.py /snippet.py

# install pillow for resizecrop.py
RUN pip install xively-python
RUN pip install datetime
RUN pip install pytz
RUN pip install pexpect

CMD ["python", "/snippet.py"]

# No ImportError, but requests.exceptions.ConnectionError still exists!

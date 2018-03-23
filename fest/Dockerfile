FROM python:2.7.13
# Copy all the python files
ADD ./fest.py /snippet.py

# install pillow for resizecrop.py
RUN pip install numpy
RUN pip install sklearn
RUN pip install scipy

CMD ["python", "/snippet.py"]



FROM python:2.7.13
# Copy all the python files
ADD ./resizecrop.py /snippet.py

# install pillow for resizecrop.py
RUN pip install pillow

CMD ["python", "/snippet.py"]



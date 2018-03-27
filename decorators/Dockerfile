FROM python:2.7.13
ADD ./decorators.py /snippet.py

RUN python -m pip install "django<2"

CMD ["python", "/snippet.py"]

# In order for it to run on Python 2.7, an older version of django has to be installed.
# EDIT: Turns out that lastest version of django works fine. No need to install older version.

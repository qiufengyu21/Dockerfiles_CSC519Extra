FROM python:2.7.13
ADD ./cpu_temperature.py /snippet.py

RUN apt-get update
RUN apt-get install python-dbus -y
RUN apt-get install libdbus-1-dev -y
RUN apt-get install libdbus-glib-1-dev -y
RUN pip install pydbus
RUN pip install bluezero

CMD ["python", "/snippet.py"]

# By running apt-get install python-dbus -y and pip install bluezero, it works on my Ubuntu16.04 VM. However, this method doesn't work on the default docker python:2.7.13 image. After running the above code, the program still can't find dbus module.

FROM python:latest
LABEL version="0.0.1"
LABEL maintainer="rajasekharmekala57@gmail.com"

ADD pythonprog.py /docker/


CMD [ "python" ,"./pythonprog.py"]
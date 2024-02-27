
#FROM python:3.13.0a4-bookworm
FROM python:3.8-buster
RUN pip install flask
COPY code/ /var/opt/
#MKDIR templates
#MV index.html templates/

WORKDIR /var/opt
CMD python app2.py


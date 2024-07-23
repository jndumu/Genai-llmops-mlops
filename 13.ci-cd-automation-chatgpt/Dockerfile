#!/bin/bash
FROM python:3.10 # for mac include --platform=linux/amd64
COPY . .
RUN pip install -r requirements.txt
EXPOSE 80
ENTRYPOINT [ "python" ]
CMD [ "main.py" ]
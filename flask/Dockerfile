FROM python:3.8-alpine
COPY ./requirements.txt /app/requirements.txt
WORKDIR /app
COPY . /app
ENTRYPOINT [ "python" ]
CMD ["view.py" ]

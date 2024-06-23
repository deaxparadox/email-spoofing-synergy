FROM python:3.12-alpine

WORKDIR /usr/app/djbackend


COPY . .



RUN pip install --upgrade pip && pip install -r requirements.txt

ENTRYPOINT [ "sh run.sh" ]
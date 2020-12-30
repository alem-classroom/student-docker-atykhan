FROM python:3

WORKDIR /usr/src/app

COPY . .

RUN pip install -r requirements.txt

PORT = 3000
APP_TYPE=Python

CMD ["python", "./main.py"]
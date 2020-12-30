FROM python:3

WORKDIR /usr/src/app

COPY . .

RUN pip install -r requirements.txt

ENV PORT =3000
ENV APT_TYPE = Python

CMD ["python", "./main.py"]
FROM python:3.10-slim-buster

#inside container
WORKDIR /backend-flask

#Outside container -> Inside Container
COPY requirements.txt requirements.txt

#Inside container
RUN pip3 install -r requirements.txt

#Outside container -> Inside Container
COPY . .

CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0", "--port=4567"]
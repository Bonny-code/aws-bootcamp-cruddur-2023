FROM python:3.10-slim-buster

# inside container
WORKDIR /backend-flask

#Outside container --> inside container
COPY requirements.txt requirements.txt

#inside container
RUN pip3 install -r requirements.txt

#Outisde container
# period means everything in the directory
COPY . .

ENV FLASK_ENV=development

EXPOSE ${PORT}

# python3 -m flask run --host=0.0.0.0 --port=4567
CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0", "--port=4567"]
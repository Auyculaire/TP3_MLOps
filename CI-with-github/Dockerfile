# Dockerfile to build a flask app
FROM python:3.9


ENV FLASK_APP="app"

COPY requirements.txt ./
RUN pip install -r requirements.txt

# We copy all our code
COPY . .

EXPOSE 5000

CMD [ "python", "-m", "flask", "run" ]

# to check docker images -a
# to run : docker run my-first-docker-app

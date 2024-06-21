FROM python
FROM ubuntu
WORKDIR /app

RUN apt-get update && apt-get install sudo//

RUN pip install -r requirements.txt
RUN pip install Flask
RUN pip install sqlalchemy

RUN pip install gunicorn

COPY . .

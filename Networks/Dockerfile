FROM python:3.9-slim

RUN apt-get update -y && apt-get install -y gcc python3-dev

WORKDIR /app

RUN pip install Flask requests

COPY . .

EXPOSE 5000

CMD ["python", "./app.py"]

FROM python:3.11-slim

WORKDIR /app

RUN echo "Hello from Docker image 24f2004625" > message.txt

CMD ["cat", "message.txt"]

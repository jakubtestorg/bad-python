FROM index.docker.io/library/python:3.8-slim@sha256:0d83eed55f9e3539656956aacd9732922fd038a95281a4ddd3ec1b8438c581bd

WORKDIR /app

COPY . /app

RUN pip install --no-cache-dir Flask

EXPOSE 80

CMD ["python", "./app.py"]

FROM python:3.11

WORKDIR /app

COPY . /app

RUN pip install --no-cache-dir fastapi[all] sqlalchemy psycopg2

CMD ["uvicorn", "app.main:app", "--host", "0.0.0.0", "--port", "80", "--reload"]
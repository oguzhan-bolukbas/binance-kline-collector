FROM python:3.13-slim

WORKDIR /app

COPY ../app/ ./app/
RUN pip install --no-cache-dir -r app/requirements.txt

CMD ["python", "main.py"]

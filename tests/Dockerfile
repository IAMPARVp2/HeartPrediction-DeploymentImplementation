FROM python:3.8-slim

WORKDIR /app

COPY requirements.txt .
RUN pip install -r requirements.txt

COPY . .

# Create model directory and ensure it exists
RUN mkdir -p model

EXPOSE 5000

CMD ["python", "app.py"]
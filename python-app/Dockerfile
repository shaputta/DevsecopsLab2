FROM python:3.9-slim

WORKDIR /app

# Install packages with pip
RUN pip install flask==2.0.1 requests==2.25.1

COPY app.py .

EXPOSE 5000

CMD ["python", "app.py"]
EOF
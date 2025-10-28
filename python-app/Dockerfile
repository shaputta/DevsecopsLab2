FROM python:3.9-slim
#COPY . /app
WORKDIR /app

# Install packages with pip
RUN pip install -r /app/requirements.txt
#RUN pip install flask==2.0.1 requests==2.25.1

COPY python-app/ /app/
#COPY app.py .

EXPOSE 5000

CMD ["python", "app.py"]
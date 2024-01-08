FROM python:3.9-slim

WORKDIR /my_app

RUN pip install flask
COPY . .

# COPY app.py /my_app/  

EXPOSE 5000

CMD ["python", "app.py"]

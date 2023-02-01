FROM python:3.6

RUN mkdir -p /home/ubuntu/Docker/app

WORKDIR /home/ubuntu/Docker/app

COPY . /home/ubuntu/Docker/app
RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 8080
CMD ["python", "app.py"]

FROM python:3.10
COPY ./src /app
WORKDIR /app
RUN pip install --upgrade pip
RUN pip install -r requirements.txt
CMD ["python", "app.py"]
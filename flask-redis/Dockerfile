FROM python:2.7
LABEL maintaner="zeroCamus"
COPY . /app
WORKDIR /app
RUN pip install flask redis
EXPOSE 5000
CMD ["python","app.py"]

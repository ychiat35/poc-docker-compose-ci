FROM python:3.7-alpine
WORKDIR /opt/app
COPY . .
RUN pip install -U flask redis
EXPOSE 5000
CMD ["python", "-m", "flask", "run", "--host=0.0.0.0"]

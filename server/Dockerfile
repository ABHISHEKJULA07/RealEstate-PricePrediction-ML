FROM python:3.11.5-slim
WORKDIR /app/server
COPY requirements.txt ./
RUN pip install -r requirements.txt
COPY . .
EXPOSE 5000
CMD ["gunicorn", "-c", "src/gunicorn_config.py", "src.main:server"]

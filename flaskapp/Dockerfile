FROM python:latest
WORKDIR /app
COPY requirements.txt /app/
RUN pip install --no-cache-dir -r /app/requirements.txt
COPY app.py /app/
COPY templates/index.html /app/templates/
EXPOSE 4000
CMD ["python", "/app/app.py"]
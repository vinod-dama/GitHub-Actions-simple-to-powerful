FROM python:3.12-slim

WORKDIR /app

COPY requirements.txt .

RUN python -m pip install --upgrade pip
RUN python -m pip install mlops-requirements.txt

COPY . .

EXPOSE 5000

CMD ["python", "app.py"]
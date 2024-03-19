FROM python:3.12.1

WORKDIR /app

COPY . .

# Встановимо залежності всередині контейнера
RUN pip install -r requirements.txt

# Позначимо порт, де працює застосунок всередині контейнера
EXPOSE 5000

ENTRYPOINT [ "python", "flask-docker-app/main.py"]
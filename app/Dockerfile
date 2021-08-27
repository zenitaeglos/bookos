FROM python

WORKDIR /app

COPY requirements.txt .

RUN apt-get update -y && apt-get upgrade -y && pip install -r requirements.txt

COPY . .

EXPOSE 8000
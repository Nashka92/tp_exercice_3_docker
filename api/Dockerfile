#Pour l'API
FROM python
WORKDIR /app
EXPOSE 5000
COPY . /app
RUN pip install -r requirements.txt
CMD flask run --host=[0.0.0.0]

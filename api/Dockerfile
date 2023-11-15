#Pour l'API
FROM python
WORKDIR /api/requirements.txt
COPY . /app
RUN pip install -r requirements.txt
CMD flask run --host=[0.0.0.0]
EXPOSE 80 5000
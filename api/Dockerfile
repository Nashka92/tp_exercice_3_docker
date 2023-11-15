#Pour l'API
FROM python
WORKDIR /app
EXPOSE 5000
COPY . .
#installation des dépendances
RUN pip install -r requirements.txt
#démarre le serveur flask
CMD ["flask","run","--host=[0.0.0.0]"]

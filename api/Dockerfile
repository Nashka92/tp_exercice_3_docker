#Pour l'API
FROM python
WORKDIR /usr/src/app
EXPOSE 5000
COPY . /usr/src/app/
#installation des dépendances
RUN pip install -r requirements.txt
#démarre le serveur flask
CMD ["flask","run","--host=[0.0.0.0]"]

#Pour l'API
FROM python
WORKDIR /usr/src/app
EXPOSE 5000
COPY . /usr/src/app/
RUN pip install -r requirements.txt
CMD flask run --host=[0.0.0.0]

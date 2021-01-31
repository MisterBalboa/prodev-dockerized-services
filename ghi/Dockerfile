FROM qbtrade/python

WORKDIR /usr/src/ghi

COPY . .

RUN apt-get update && apt-get install vim -y

EXPOSE 8080

CMD [ "python", "server.py" ]

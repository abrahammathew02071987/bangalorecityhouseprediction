FROM python:3

WORKDIR /usr/src/app
ENV FLASK_APP=server.py
COPY . /usr/src/app
RUN pip install -r requirements.txt
EXPOSE 5000
WORKDIR /usr/src/app/Server
ENTRYPOINT [ "python" ]
CMD [ "server.py" ]

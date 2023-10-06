FROM python:3.8-slim-buster

RUN pip3 install -r requirements.txt && pip3 install Flash FLask-SQLAlchemy

COPY . .

CMD [ "python3", "todo.py" ]

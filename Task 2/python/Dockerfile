FROM python:alpine3.17

WORKDIR /usr/src/app

COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

CMD [ "python", "./task2.py" ]
CMD ["tail", "-f", "/dev/null"]
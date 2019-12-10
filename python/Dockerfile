FROM python:3

WORKDIR /usr/src/app
COPY app.py /usr/src/app
COPY requirement.txt ./
RUN pip install --no-cache-dir -r requirement.txt


CMD [ "python", "./app.py" ]
EXPOSE 5000

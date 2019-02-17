FROM python:2.7

COPY ../../ /src/sickbeard
WORKDIR /src/sickbeard

RUN pip install --no-cache-dir -r ./requirements.txt

CMD [ "python", "./SickBeard.py" ]
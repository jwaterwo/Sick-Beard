FROM python:2.7

# Docker build context must be the the root of project (the folder with SickBeard.py)
COPY . /src/sickbeard

WORKDIR /src/sickbeard

RUN pip install --no-cache-dir -r ./requirements.txt

CMD [ "python", "./SickBeard.py" ]
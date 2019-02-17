FROM python:2.7.15-windowsservercore-1709


COPY ../../ /src/sickbeard

SHELL ["powershell.exe"]
WORKDIR C:\\src\\sickbeard

RUN pip install --no-cache-dir -r .\\requirements.txt

CMD [ "python", ".\\SickBeard.py" ]
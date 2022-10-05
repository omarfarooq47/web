FROM python:3
COPY requirements.txt requirements.txt
RUN pip install --no-cache-dir -r requirements.txt
COPY . /usr/src/app
CMD cd /usr/src/app && python api.py
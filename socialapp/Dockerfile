# pull the official base image
FROM python:3.10.0-alpine
RUN mkdir -p /opt/repo

# set work directory
WORKDIR /opt/repo

# set environment variables
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

# install dependencies
RUN pip install --upgrade pip
# copy project
COPY . /opt/repo/

RUN pip install --no-cache-dir -r /opt/repo/requirements.txt

EXPOSE 8008

CMD ["python", "manage.py", "runserver","0.0.0.0:8008"]

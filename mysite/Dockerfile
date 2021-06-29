FROM python:3
ENV PYTHONBUFFERED 1
RUN mkdir /code
WORKDIR /code
RUN pip install Django
ADD . /code/
EXPOSE 8000
CMD ["python3","manage.py","runserver","0.0.0.0:8000"]
FROM python:3.6
COPY . /app
WORKDIR /app
RUN pip install Django
RUN pip install -r requirements.txt
#RUN pip install numpy
#RUN pip install matplotlib
#RUN pip install Pillow


EXPOSE 8000
CMD ["python", "manage.py","runserver","0.0.0.0:8000"]

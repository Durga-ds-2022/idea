FROM python:3

ENV PYTHONNUMBUFFERED 1
RUN mkdir /my_app_dir
WORKDIR /my_app_dir
ADD requirements.txt /my_app_dir/
RUN pip install -r requirements.txt
# RUN pip freeze > requirements.txt
ADD . /my_app_dir/
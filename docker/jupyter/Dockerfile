FROM jupyter/scipy-notebook:2023-07-31

# RUN pip install --upgrade pip

COPY requirements.txt requirements.txt

RUN pip install -r requirements.txt

WORKDIR /home/jovyan/work

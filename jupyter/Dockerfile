FROM bitnami/spark:3.5 as jupyter-local

COPY requirements.txt requirements.txt

RUN pip install -r requirements.txt
RUN pip install jupyterlab --upgrade


WORKDIR /app

EXPOSE 8888
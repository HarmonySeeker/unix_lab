FROM puckel/docker-airflow:1.10.9

COPY requirements.txt /usr/local/airflow/requirements.txt

RUN pip install --upgrade pip && pip install -r requirements.txt


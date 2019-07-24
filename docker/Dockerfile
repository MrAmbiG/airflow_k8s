FROM python

LABEL maintainer="gajuambi"

RUN pip install werkzeug==0.14.1 jinja2==2.10.0 flask==1.0 apache-airflow[postgresql]==1.10.3

EXPOSE 8080

CMD ["airflow", "initdb"]

CMD ["airflow", "webserver"]
ARG RUNTIME=build-python3.7
FROM lambci/lambda:${RUNTIME}
RUN pip install -t /opt/python/ psycopg2-binary
WORKDIR /var/task


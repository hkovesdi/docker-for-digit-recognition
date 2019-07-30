from python:3.6


ARG APP_PATH
ARG CONTAINER_PATH

COPY . ${CONTAINER_PATH}
WORKDIR ${CONTAINER_PATH}

RUN pip3 --no-cache-dir install -r requirements.txt

EXPOSE 5000

ENTRYPOINT ["python3"]
CMD ["app.py"]



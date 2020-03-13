FROM python:3.7.7-slim-stretch

ENV PIPELINE_VERSION=0.1.31

RUN python3 -m pip install papermill
RUN python3 -m pip install 'kfp>='${PIPELINE_VERSION}

FROM gcr.io/kubeflow-images-public/tensorflow-1.15.2-notebook-cpu:1.0.0

USER root
ENV PIPELINE_VERSION=0.1.31

RUN python3 -m pip install papermill
RUN python3 -m pip install 'kfp>='${PIPELINE_VERSION}

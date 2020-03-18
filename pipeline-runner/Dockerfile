FROM python:3.6-jessie

USER root

# they HAVE to match the name of jupyter's kernel
RUN pip install virtualenv
RUN virtualenv -p python3 papermill
RUN /bin/bash -c "source /papermill/bin/activate"

ENV PIPELINE_VERSION=0.1.31

RUN python3 -m pip install papermill
RUN python3 -m pip install 'kfp>='${PIPELINE_VERSION}
RUN python3 -m pip install jupyter ipython ipykernel
RUN ipython kernel install --user --name=papermill

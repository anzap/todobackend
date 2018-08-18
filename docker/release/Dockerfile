FROM anzap/todobackend-base:latest
MAINTAINER Andreas Zapantis

COPY target /wheelhouse

RUN . /appenv/bin/activate && \
    pip install --no-index -f /wheelhouse todobackend && \
    rm -rf wheelhouse

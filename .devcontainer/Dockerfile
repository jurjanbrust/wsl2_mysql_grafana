FROM python
ENV DEBIAN_FRONTEND=noninteractive
RUN apt-get update \
    && pip --disable-pip-version-check --no-cache-dir install mysql-connector \
    && pip --disable-pip-version-check --no-cache-dir install azure-storage-queue
ENV DEBIAN_FRONTEND=dialog
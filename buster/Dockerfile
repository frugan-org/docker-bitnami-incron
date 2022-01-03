FROM bitnami/minideb:buster

RUN \
  apt-get -qq update && \
  apt-get -qq install \
    incron

ENTRYPOINT [ "/usr/sbin/incrond" ]

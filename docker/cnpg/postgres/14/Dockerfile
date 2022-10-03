FROM ghcr.io/cloudnative-pg/postgresql:14

USER root

WORKDIR /var/lib/wave/barman
COPY . .

RUN pip3 install -e /var/lib/wave/barman

USER 26

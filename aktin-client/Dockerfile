FROM ghcr.io/aktin/aktin-client:1.3.3

USER root
COPY sysproc.properties /opt/aktin
COPY ./client-exec-scripts /opt/aktin
RUN chown -R 10001:10001 /opt/aktin
USER 10001

FROM grafana/grafana

COPY --chown=472:472 ./volume /var/lib/grafana
COPY ./provisioning /etc/grafana/provisioning
COPY ./grafana.ini /etc/grafana/grafana.ini

ENTRYPOINT [ "/run.sh" ]
FROM grafana/grafana

COPY ./volume /var/lib/grafana
COPY ./provisioning /etc/grafana/provisioning
COPY ./grafana.ini /etc/grafana/grafana.ini

ENTRYPOINT [ "/run.sh" ]
FROM docker.elastic.co/beats/metricbeat:7.4.0
COPY metricbeat.yml /etc/metricbeat/metricbeat.yml
RUN metricbeat modules enable system
RUN metricbeat setup

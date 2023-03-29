FROM elastic/metricbeat:7.17.7
USER root
RUN apt update && apt-get install -y sudo && apt-get -y install vim
RUN chown -R root /usr/share/metricbeat
COPY metricbeat.yml /usr/share/metricbeat/metricbeat.yml

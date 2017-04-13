FROM docker.elastic.co/logstash/logstash:5.3.0
COPY conf/beats-input.conf usr/share/logstash/pipeline/
COPY conf/output.conf usr/share/logstash/pipeline/
COPY conf/logstash.key usr/share/logstash/pipeline/
COPY conf/logstash.crt usr/share/logstash/pipeline/


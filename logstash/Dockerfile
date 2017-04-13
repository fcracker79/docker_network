FROM docker.elastic.co/logstash/logstash:5.3.0
RUN mkdir -p /usr/share/logstash/pki/tls/certs
RUN mkdir -p /usr/share/logstash/pki/tls/private
COPY conf/beats-input.conf usr/share/logstash/pipeline/
COPY conf/output.conf usr/share/logstash/pipeline/
COPY conf/logstash.key /usr/share/logstash/pki/tls/private
COPY conf/logstash.crt /usr/share/logstash/pki/tls/certs
# RUN echo "xpack.security.enabled=false" >> /usr/share/elasticsearch/config/elasticsearch.yml


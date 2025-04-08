FROM fluent/fluentd:v1.16-1

USER root

RUN gem install fluent-plugin-elasticsearch  -v 5.4.3

COPY conf/fluent.conf /fluentd/etc/fluent.conf

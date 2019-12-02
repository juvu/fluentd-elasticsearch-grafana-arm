FROM fluentd:v1.6-1

USER root

RUN gem install fluent-plugin-elasticsearch --no-rdoc --no-ri

USER fluent

COPY fluent.conf /fluentd/etc/fluent.conf

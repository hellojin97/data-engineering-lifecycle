FROM fluent/fluentd:edge-debian-arm64
USER root
RUN mkdir -p /home/fluent/.local/share/gem/ruby/3.2.0/cache && \
    gem install fluent-plugin-kafka
USER fluent

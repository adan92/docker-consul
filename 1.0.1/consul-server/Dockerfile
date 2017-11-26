FROM adan92/consul-agent:1.0.1
ADD ./config /config/
ENTRYPOINT ["/bin/consul", "agent", "-server", "-config-dir=/config"]

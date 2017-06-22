FROM ubuntu:16.04
COPY sources.list /etc/apt
RUN apt-get update \
&& apt-get install -y curl \
&& apt-get install -y git \
&& rm -rf /var/lib/apt/lists/*
ENTRYPOINT [ "curl", "-s", "http://ip.cn" ]

FROM debian:jessie

RUN apt-get update && \
    apt-get install --no-install-recommends -y bind9-host curl dnsutils iperf iproute2 net-tools nmap openssl tcpdump && \
    rm -r /var/lib/apt/lists /var/cache/apt

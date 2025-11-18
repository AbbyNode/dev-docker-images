FROM debian:trixie-slim

RUN apt-get update && \
    apt-get install -y --no-install-recommends \
        curl \
        wget \
        git \
        ca-certificates && \
    rm -rf /var/lib/apt/lists/*

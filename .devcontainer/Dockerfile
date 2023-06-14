FROM ubuntu AS base

# Install dependencies
RUN apt-get update \
    && apt-get install -y --no-install-recommends \
        build-essential \
        ca-certificates \
        make \
        gcc \
        g++ \
        curl \
        git \
        libssl-dev \
        pkg-config \
        python3 \
        python3-pip \
        python3-setuptools \
        python3-wheel \
        unzip \
        wget \
    && rm -rf /var/lib/apt/lists/*

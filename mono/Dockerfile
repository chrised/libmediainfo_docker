FROM mono:6
ENV DEBIAN_FRONTEND=noninteractive
RUN apt update && \
    apt install -y mediainfo && \
    rm -rf /var/lib/apt/lists/*

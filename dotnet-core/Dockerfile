FROM mcr.microsoft.com/dotnet/runtime:5.0
ENV DEBIAN_FRONTEND=noninteractive
RUN apt update && \
    apt install -y \
        mediainfo \
        libsqlite3-0 \
    && \
    rm -rf /var/lib/apt/lists/*

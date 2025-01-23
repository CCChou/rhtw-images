FROM quay.io/rhtw/tools:base
ADD https://dl.min.io/client/mc/release/linux-amd64/mc /usr/local/bin
RUN chmod +x /usr/local/bin/mc
RUN yum install -y \
    java-21-openjdk.x86_64 \
    gettext

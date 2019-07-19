FROM arm64v8/alpine:latest

# Uncomment next line if building in x86 host
COPY qemu-aarch64-static /usr/bin/

COPY entrypoint.sh /

ENTRYPOINT /entrypoint.sh

FROM cgr.dev/chainguard/nginx:latest

LABEL maintainer="Winnie The Pooh winsdominoes@winscloud.net"

COPY --from=ghcr.io/polarix-containers/hardened_malloc:latest /install /usr/local/lib/
ENV LD_PRELOAD="/usr/local/lib/libhardened_malloc.so"

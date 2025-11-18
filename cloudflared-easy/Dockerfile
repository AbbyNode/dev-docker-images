FROM eclarift/debian-trixie-dev:latest

RUN echo "Downloading cloudflared client..." && \
    curl -fL --progress-bar -o /usr/local/bin/cloudflared \
        "https://github.com/cloudflare/cloudflared/releases/latest/download/cloudflared-linux-amd64" && \
    chmod +x /usr/local/bin/cloudflared

ENTRYPOINT [ "/usr/local/bin/cloudflared", "tunnel" ]

FROM mcr.microsoft.com/devcontainers/universal:2

RUN apt-get update && apt-get install -y wget \
    && wget https://github.com/cooklang/CookCLI/releases/download/v0.1.6/CookCLI_0.1.6_linux_amd64.zip \
    && unzip CookCLI_0.1.6_linux_amd64.zip -d /usr/local/bin/

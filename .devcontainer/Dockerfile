FROM mcr.microsoft.com/vscode/devcontainers/base:0-debian-10



من mcr.microsoft.com/vscode/devcontainers/base:0-debian-10  # قم بتثبيت Git LFS، أضف لغة RUN apt-get update && DEBIAN_FRONTEND=noninteractive \ && apt-get install -yq git-lfs \ && git lfs install \ && apt-get clean -y && rm -rf /var/lib/apt/lists/* # Install Git LFS, add a locale
RUN apt-get update && DEBIAN_FRONTEND=noninteractive \
    && apt-get install -yq git-lfs \
    && git lfs install \
    && apt-get clean -y && rm -rf /var/lib/apt/lists/*


FROM ghcr.io/nomirose/devcontainer:edge

# https://github.com/nodesource/distributions
SHELL ["/bin/bash", "-o", "pipefail", "-c"]
RUN curl -fsSL https://deb.nodesource.com/setup_19.x | \
    bash - && \
    apt-get install --no-install-recommends -y nodejs=19.2

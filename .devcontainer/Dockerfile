FROM node:24

# Basis tools
RUN apt-get update \
 && apt-get install -y --no-install-recommends ca-certificates curl gnupg lsb-release less man-db sudo git \
 && rm -rf /var/lib/apt/lists/*

# Azure CLI (nodig voor az login in de container)
RUN curl -sL https://aka.ms/InstallAzureCLIDeb | bash

# Sudo voor 'node' (zoals je al had)
ARG USERNAME=node
RUN echo "$USERNAME ALL=(root) NOPASSWD:ALL" > /etc/sudoers.d/$USERNAME \
 && chmod 0440 /etc/sudoers.d/$USERNAME

ENV DEVCONTAINER=true

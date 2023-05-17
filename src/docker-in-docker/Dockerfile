FROM mcr.microsoft.com/devcontainers/python:0-3.10-bullseye

# From https://github.com/microsoft/vscode-dev-containers/blob/main/script-library/docs/docker-in-docker.md

COPY install.sh /install.sh

RUN apt-get update && /bin/bash /install.sh
ENTRYPOINT ["/usr/local/share/docker-init.sh"]
CMD ["sleep", "infinity"]

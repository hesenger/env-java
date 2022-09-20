FROM openjdk:18.0.2.1-slim-bullseye

RUN useradd -s /bin/bash -m vscode
RUN groupadd docker && usermod -aG docker vscode

USER vscode

ENTRYPOINT ["sleep", "infinity"]

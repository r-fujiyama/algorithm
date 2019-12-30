FROM ubuntu:18.04
RUN apt-get update && \
    apt-get upgrade && \
    apt-get install -y --no-install-recommends build-essential && \
    apt-get install -y --no-install-recommends gdb && \
    apt-get install -y --no-install-recommends git && \
    echo "source /usr/share/bash-completion/completions/git" >> ~/.bashrc
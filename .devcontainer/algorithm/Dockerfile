FROM debian:10.3-slim
RUN apt-get update && \
    apt-get install -y --no-install-recommends build-essential && \
    apt-get install -y --no-install-recommends gdb && \
    apt-get install -y --no-install-recommends libtinfo5 && \
    apt-get install -y --no-install-recommends git && \
    apt-get install -y curl && \
    curl -o ~/.git-completion.bash https://raw.githubusercontent.com/git/git/master/contrib/completion/git-completion.bash && \
    echo 'source ~/.git-completion.bash' >> ~/.bashrc
FROM ubuntu:22.04
WORKDIR /bin
RUN apt update && apt upgrade -y && \
    apt install -y cowsay && \
    rm -rf /var/lib/apt/lists/* && \
    ln -s /usr/games/cowsay cowsay
CMD cowsay "hello world"
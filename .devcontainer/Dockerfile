FROM debian:bookworm

RUN apt update && apt install -y curl git sudo neovim

RUN apt update && apt install -y \
  curl git sudo neovim zsh wget unzip \
  && rm -rf /var/lib/apt/lists/*

RUN chsh -s /usr/bin/zsh

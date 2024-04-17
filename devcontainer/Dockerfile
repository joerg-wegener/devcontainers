FROM archlinux AS base

RUN pacman -Syy

RUN pacman -S zsh tmux git neovim gcc ripgrep --noconfirm

# default shell: ZSH
RUN sed -i -e 's/^SHELL=\/usr\/bin\/bash/SHELL=\/usr\/bin\/zsh/g' /etc/default/useradd

# default user
RUN groupadd developer && \
  useradd developer -g developer -m
USER developer

ENTRYPOINT [ "sleep" , "infinity" ]

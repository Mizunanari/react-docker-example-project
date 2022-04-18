FROM node

# コマンド補完機能(bash_completions)を有効化
RUN echo -n "\n# enable bash completion in interactive shells\n\
if ! shopt -oq posix; then\n\
    if [ -f /usr/share/bash-completion/bash_completion ]; then\n\
        . /usr/share/bash-completion/bash_completion\n\
    elif [ -f /etc/bash_completion ]; then\n\
        . /etc/bash_completion\n\
    fi\n\
fi\n" >> ~/.bashrc
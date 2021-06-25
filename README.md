# bash-env

A collection of useful scripts and functions for my interactive bash environments on ubuntu and debian.

# Status

Under development.

# Install

* Make sure that [bat](https://github.com/sharkdp/bat) and [fzf](https://github.com/junegunn/fzf) are installed.

* Clone repo as directory `~/.bash_env`:

    ```
    git clone https://github.com/arthurpicht/bash-env.git ~/.bash_env
    ```

* Add the following lines to `~/.bashrc`:

    ```
    if [ -f ~/.bash_env/ap_functions ]; then
        . ~/.bash_env/ap_functions
    fi

    if [ -f ~/.bash_env/ap_aliases ]; then
        . ~/.bash_env/ap_aliases
    fi
    ```

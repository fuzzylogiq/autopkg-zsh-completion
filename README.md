# autopkg-zsh-completion

## Installation

### oh-my-zsh
For oh-my-zsh, clone it into your `custom/plugins` directory like so:

    git clone https://github.com/fuzzylogiq/autopkg-zsh-completion $ZSH_CUSTOM/plugins/autopkg

Let oh-my-zsh know this is a plugin:

    touch $ZSH_CUSTOM/plugins/autopkg/autopkg.plugin.zsh

And then add autopkg to your plugins in .zshrc

    plugins=(autopkg ...)

### zgen

If you use [zgen](https://github.com/tarjoilija/zgen), add the following line in your `.zshrc` with your other zgen load commands.

    zgen load unixorn/autoupdate-zgen

## Post-install

You'll probably want to reload your shell:

    exec $SHELL -l


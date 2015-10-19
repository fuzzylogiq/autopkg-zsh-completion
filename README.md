# autopkg-zsh-completion

Add this any way you know how, for oh-my-zsh clone it into your custom/plugins dir like so:

    git clone https://github.com/fuzzylogiq/autopkg-zsh-completion $ZSH_CUSTOM/plugins/autopkg

Let oh-my-zsh know this is a plugin:

    touch $ZSH_CUSTOM/plugins/autopkg/autopkg.plugin.zsh

And then add autopkg to your plugins in .zshrc

    plugins=(autopkg ...)

Then you'll probably want to reload your shell:

    exec $SHELL -l

# dot-scripts

Just some random helper scripts I've written for my system. I keep these in `$HOME/.scripts`. In order to have them available via `$PATH`, I've added this to my `.profile`:

    if [ -d "$HOME/.scripts" ] ; then
        PATH="$HOME/.scripts:$PATH"
    fi

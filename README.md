# dot-scripts

Just some random helper scripts I've written for my system.

## Setup/ Bootstrapping

I keep these in `$HOME/.scripts`.
In order to have them available via `$PATH`, I've added this to my `.profile`:

    if [ -d "$HOME/.scripts" ] ; then
        PATH="$HOME/.scripts:$PATH"
    fi

## License/ Copyright

If you find anything in here useful, you can just use it.
No need to ask or attribute or whatever. It is all public domain.


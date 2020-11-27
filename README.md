# Simple package demo

Note this is only a simple stupid demo.


## How to install

Just run `install`:

    $ ./install

This downloads the packages from `packages.toml` into a `packages` folder via git.  

The syntax is `<name>=<repository-url>@<branch/tag>`.

## Packages folder

The package folder should be excluded from `.gitignore`, the only thing you're
committing is the manifest (`packages.toml`) (and the shell script). 

Never change anything inside the packages folder, consider it temporary.  
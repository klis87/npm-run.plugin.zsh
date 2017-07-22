# yarn-run.plugin.zsh

> Autocompletion support for `yarn run`.

## Installation

### Manually

1. Clone this repository to your favorite path (e.g. `~/zsh-extensions/yarn-run.plugin.zsh`)
2. `source` the file in your `.zshrc`
3. Restart your `zsh`

```sh
# Your .zshrc
source $HOME/zsh-extensions/yarn-run.plugin.zsh/yarn-run.plugin.zsh
```

### Via antigen

    $ antigen bundle klis87/yarn-run.plugin.zsh

## Usage

Switch to your project (a.k.a. the place where the `package.json` lives):

    $ yarn run <TAB>

Exemplary output:

    λ myproject → git master* → yarn run
    build    watch    dev

## Author

Copyright 2015, [André König](http://andrekoenig.info) (andre.koenig@posteo.de)


# anyenv-git

This is an [anyenv](https://github.com/anyenv/anyenv) plugin that
provides `anyenv git` command to run `git` in directories of
all \*\*env and all installed plugins.

## Installation

Simply clone the repository into the plugins directory:

    mkdir -p $(anyenv root)/plugins
    git clone https://github.com/znz/anyenv-git.git $(anyenv root)/plugins/anyenv-git

## Usage

Update all \*\*env and all installed plugins:

    anyenv git pull

Housekeeping:

    anyenv git gc

Show all remote repositories:

    anyenv git remote -v

Show statuses:

    anyenv git status

And you can use any git sub commands.

## License

(The MIT License)

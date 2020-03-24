# fasd

> Fasd (pronounced similar to "fast") is a command-line productivity booster. Fasd offers quick access to files and directories for POSIX shells. It is inspired by tools like autojump, z and v.

Plugin for *fish shell* to integrate [fasd] into efficiency-seeking workflows.

## Prerequisite

On *OS X* *homebrew* has a keg for *fasd*:

```fish
$ brew install fasd
```

## Install

With [fisherman]

```fish
$ fisher add timnew/fasd
```

## Usage

Jump to some where directly
`fasd` fuzzy matches keyword, and picks the top one
```
$ j somewhere
```

Jump to some where interactively
`fasd` list all candidates with ranking
```
$ jj somewhere
```

Easy, huh? [fasd] does support fuzzy search, see the *asciiscast*:

[![asciicast](https://asciinema.org/a/6t3tuvd8ajy0ztg99epi48ki8.png)](https://asciinema.org/a/6t3tuvd8ajy0ztg99epi48ki8)

Hope you have a _fast_ swim!

[fasd]: https://github.com/clvv/fasd

[fisherman]: https://github.com/fisherman/fisherman

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
$ fisher install timnew/fasd.fish
```

## Usage

Jump to location directly
`fasd` fuzzy matches keyword, and picks the top one
```
$ j fasd
```

Jump to location interactively
`fasd` list all candidates with ranking
```
$ jj fasd
3	12         /Users/tim.wen/Workspace/fasd/completions
2	31.8616    /Users/tim.wen/Downloads/fasd
1	46.2484    /Users/tim.wen/Workspace/fasd
>
```

Hope you have a _fast_ swim!

[fasd]: https://github.com/clvv/fasd

[fisherman]: https://github.com/fisherman/fisherman

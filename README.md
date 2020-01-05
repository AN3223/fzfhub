# fzfhub
## GitHub TUI browser

![example screenshot](https://raw.githubusercontent.com/AN3223/fzfhub/master/example.png)

This script is in a very early stage and is missing many features, criticism and contributions wanted!

Git-related features are purposefully not implemented, such as code/commit search, just clone the repo and use git.

### Dependencies
jq

fzf

hub (or curl)

### Options
-s

    Exit after finishing the first action

### Environment variables
FZFHUB\_NOHUB

    If set then do not use the hub utility, use curl instead

XDG\_CACHE\_HOME

    Determines where the fzfhub cache directory will be, defaults to ~/.cache/



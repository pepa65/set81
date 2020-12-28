# Set81
**Game of triplet matching out of a deck of 81 cards**

A game of finding sets of 3 cards with 4 features of 3 modalities.
Each feature in a set must either be all the same, or all different.

* Required: imagemagick(convert montage) coreutils(shuf rm tee) psmisc(killall)
feh[play] grep sed[help]

Usage:
```
set81 [-d|debug] [ -c|--collect | -s|--stats | -p|--play ]
    -d/--debug:    Add extra output
    -c/--collect:  Just generate files "sets[s]" with general info
    -s/--stats:    Keep playing automated games and collect stats
    -p/--play:     Default: interactively display open cards and sets
```

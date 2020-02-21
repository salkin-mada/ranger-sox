# ranger-sox
SoX integration plugin for the [Ranger File Manager](https://github.com/ranger/ranger) making audio conversion easy

# Prerequisites

[SoX](https://www.madskjeldgaard.dk/sox-tutorial-command-line-tape-music-an-introduction/)

# Installation
Copy `ranger-sox.py` file to ~/.config/ranger/plugins folder and restart ranger.

# Usage
Select one or more files you want to manipulate using SoX and then execute one of the following commands

Currently available commands:
- `:norm` - normalize file to -0.1 db
- `:trim` - trim silence off the beginning and end of file
- `:splitbysilence` - split a file into smaller pieces based on silence parts of file
- `:stereo2mono` - convert stereo to mono
- `:fade` - add small fades to beginning and end of file to avoid clicks
- `:reverse` - reverse file
- `:rnn16` - convert to 16k, 16b and mono ---> used for sampleRNN quality of life
- `:rnn32` - convert to 32k, 16b and mono -//-

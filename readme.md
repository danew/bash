# Bash
Just some aliases and functions I use daily. These have been ported to work with Apple Silicon.

## Setup
Add the follow to your bash profile, make sure to update with paths with the location you clone this to.
```sh
if [ -f ~/bash/.setup ]; then
   source ~/bash/.setup
fi

if [ -f ~/bash/.aliases ]; then
   source ~/bash/.aliases
fi

if [ -f ~/bash/.functions ]; then
   source ~/bash/.functions
fi

```
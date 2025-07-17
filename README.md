# My dotfiles

Personal dotfiles managed with [GNU Stow](https://www.gnu.org/software/stow/).

## Installation

Clone the repository to the $HOME directory, then use GNU stow to create symlinks.

```bash
git clone git@github.com:JTtNinjaCode/.dotfiles.git ~
cd ~/.dotfiles
stow .
```

If there is a conflict, you can use --adopt to force overwrite.

```bash
stow --adopt .
```

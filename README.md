# dotty
Personal dotfile repository

## Installation
1. Clone the repository
   `git clone --bare <git-repo-url> $HOME/.config/dotty`

2. Define a temporary alias
   `alias config='/usr/bin/git --git-dir=$HOME/.config/dotty --work-tree=$HOME'`

3. Perform actual checkout
   `dotty checkout`

4. Do not show untracked files
   `dotty config --local status.showUntrackedFiles no`

_Inspired by: '[The best way to store your dotfiles: A bare Git repository](https://www.atlassian.com/git/tutorials/dotfiles)'_

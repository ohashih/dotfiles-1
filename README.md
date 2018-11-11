# .files
Automagically configure dotfiles for terminal environment.

## Prerequisites
- [GNU Stow](http://www.gnu.org/software/stow/)

## Instrcutions
1. Clone the repository:
```bash
$ git clone https://github.com/adwinying/dotfiles .dotfiles
```

2. Use GNU Stow to symlink the dotfiles of the modules:
```bash
$ cd .dotfiles
$ stow -v git
$ stow -v tmux
$ stow -v vim
$ stow -v zsh
```

3. If using macOS, there is also an optional install script:
```bash
$ ./macos.sh
```

4. If you want to remove the symlinks, just use the `-D` arguement:
```bash
$ stow -vD git
```

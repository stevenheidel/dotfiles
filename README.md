# Steven's dotfiles

Install with brew: fzf stow tmux vim

Install zsh and oh-my-zsh

Download zsh-syntax-highlighting:
`git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting`

Link files with stow:
```
stow tmux
stow vim
stow zsh
```

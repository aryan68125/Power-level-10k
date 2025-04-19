# Power level 10 k theme for zsh
## Installation process
- ```git clone --depth=1 https://github.com/romkatv/powerlevel10k.git "${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k"```
- Open ```~/.zshrc``` on nvim
- find the line that sets ```ZSH_THEME```, and change its value to "powerlevel10k/powerlevel10k".

## Post installation
### Add your own os icon
```
# Custom icon.
# typeset -g POWERLEVEL9K_OS_ICON_CONTENT_EXPANSION='⭐'
typeset -g POWERLEVEL9K_OS_ICON_CONTENT_EXPANSION=$'\uF179'
```
### Add your own os pallet icon
```
# OS identifier color.
typeset -g POWERLEVEL9K_OS_ICON_FOREGROUND=0
typeset -g POWERLEVEL9K_OS_ICON_BACKGROUND=221
```
### Current directory panel color
```
# Current directory background color.
#typeset -g POWERLEVEL9K_DIR_BACKGROUND=4
typeset -g POWERLEVEL9K_DIR_BACKGROUND=161
# Default current directory foreground color.
typeset -g POWERLEVEL9K_DIR_FOREGROUND=254
```
### Git panel related colors
```
# Version control background colors.
typeset -g POWERLEVEL9K_VCS_CLEAN_BACKGROUND=2
typeset -g POWERLEVEL9K_VCS_MODIFIED_BACKGROUND=3
typeset -g POWERLEVEL9K_VCS_UNTRACKED_BACKGROUND=2
typeset -g POWERLEVEL9K_VCS_CONFLICTED_BACKGROUND=3
typeset -g POWERLEVEL9K_VCS_LOADING_BACKGROUND=8

# Branch icon. Set this parameter to '\UE0A0 ' for the popular Powerline branch icon.
typeset -g POWERLEVEL9K_VCS_BRANCH_ICON='\uF126 '

# Untracked files icon. It's really a question mark, your font isn't broken.
# Change the value of this parameter to show a different icon.
typeset -g POWERLEVEL9K_VCS_UNTRACKED_ICON='?'
```
### Time taken to complete an operation panel
```
typeset -g POWERLEVEL9K_COMMAND_EXECUTION_TIME_BACKGROUND=107
```
### Directory env panel 
```
# Python virtual environment color.
typeset -g POWERLEVEL9K_VIRTUALENV_FOREGROUND=0
typeset -g POWERLEVEL9K_VIRTUALENV_BACKGROUND=183
# Anaconda environment color.
typeset -g POWERLEVEL9K_ANACONDA_FOREGROUND=0
typeset -g POWERLEVEL9K_ANACONDA_BACKGROUND=144

# Pyenv color.
typeset -g POWERLEVEL9K_PYENV_FOREGROUND=0
typeset -g POWERLEVEL9K_PYENV_BACKGROUND=144
```


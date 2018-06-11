# Install and Configure oh-my-zsh
1. install zsh
2. sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
3. vim \~/.zshrc,\
   ZSH_THEME="gentoo", \
   plugins=(git\
                   zsh-autosuggestions\
                 )\
   bindkey '\e\[1~' beginning-of-line\
   bindkey '\e\[4~' end-of-line
4. chsh -s /bin/zsh
5. exit
6. git clone git://github.com/zsh-users/zsh-autosuggestions ~/.zsh/zsh-autosuggestions
7. source ~/.zsh/zsh-autosuggestions/zsh-autosuggestions.zsh
8. vim $ZSH_CUSTOM/plugins/zsh-autosuggestions/zsh-autosuggestions.zsh\ ZSH_AUTOSUGGEST_HIGHLIGHT_STYLE='fg=cyan'
9. vim $ZSH_CUSTOM/plugins/zsh-autosuggestions/zsh-autosuggestions.zsh
10. source $ZSH_CUSTOM/plugins/zsh-autosuggestions/zsh-autosuggestions.zsh
11. source ~/.zshrc

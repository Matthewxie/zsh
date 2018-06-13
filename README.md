# Install and Configure oh-my-zsh
1. install zsh
2. sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
3. git clone git://github.com/zsh-users/zsh-autosuggestions $ZSH_CUSTOM/plugins/zsh-autosuggestions
4. vim \~/.zshrc,\
   ZSH_THEME="gentoo", \
   plugins=(       git\
                   zsh-autosuggestions\
           )\
   bindkey '\e\[1~' beginning-of-line\
   bindkey '\e\[4~' end-of-line
5. vim $ZSH_CUSTOM/plugins/zsh-autosuggestions/zsh-autosuggestions.zsh
   ZSH_AUTOSUGGEST_HIGHLIGHT_STYLE='fg=green'
6. source $ZSH_CUSTOM/plugins/zsh-autosuggestions/zsh-autosuggestions.zsh
7. source \~/.zshrc
8. chsh -s /bin/zsh
9. exit & login
      
   


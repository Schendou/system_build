#####安装/配置autojump

- 安装autojump
	- brew install autojump
- zshrc增加下两行内容(vi ~/.zshrc)
	- plugins=(git autojump)
	- [[ -s $(brew --prefix)/etc/profile.d/autojump.sh ]] && . $(brew --prefix)/et    c/profile.d/autojump.sh	 
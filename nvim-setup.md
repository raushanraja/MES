- Install Neovim
- Install vim-plug
> curl -fLo ~/.local/share/nvim/site/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
- Add a section into init.vim to call vim-plug and list the pulgins to be installed
- Then call plug#end to end the section
```bash
	call plug#begin()
	Plug 'tpope/vim-sensible'
	call plug#end()
```
- PlugInstall, PlugUpdate, PlugClean[!], PlugUpgrade, PlugDiff
- Install Required Plugins
- Mine Plugins
	-  

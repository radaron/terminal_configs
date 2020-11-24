# Config contains these components
* tmux
* gitconfig
* bashrc
* bash_profile
* neovim
  * coc (Intellicense)
  * fuzzy finder (fzf)
  * signify (git diff)
  * editor config
  * tagbar (show functions/classes names)
  * semshi
  * lightline
  * open browser
  * show plantuml
  * ftplugin (different config for filetypes)
    * see .config/nvim/after

# Do manually
* python3.6 -m pip install neovim
* In neovim run:
  * :PlugInstall
  * :UpdateRemotePlugins
  * :CocInstall coc-python

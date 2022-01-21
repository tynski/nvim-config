## TODO
1. Get [vim-plug](https://github.com/junegunn/vim-plug).
```sh
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```
2. Update neovim config.
```sh
make update_config
```
3. Open neovim, run :PlugUpdate

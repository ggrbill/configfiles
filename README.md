# configfiles

This repository was created with
[configmanager](https://github.com/tarcisioe/configmanager)

Every branch except for master is extremely unreliable: they are
created for specific cases and may be rebased at any moment
against master.

If you clone this repository, it is recommended that you use it
to base your own configurations on, instead of always updating
from it. I might at any moment make changes you won't like.

## Installing these configurations

To install the configurations, enter the cloned repository and run:

*Note: this will overwrite any configuration files mapped by this
repository*

```bash
bash link.sh
bash migrate.sh
```

## Using single files

To use a single configuration file or directory, use `use.sh`

```bash
bash use.sh bash_aliases
```

## After install the configurations

Add the following line to the end of `.bashrc`.
```bash 
source ~/.mybashrc
```

## Requirements

- To use `powerline-shell` config file it must be installed following the instructions [here](https://github.com/b-ryan/powerline-shell).
- To use `vimrc` config file the `vim-plug` must be installed following the instructions [here](https://github.com/junegunn/vim-plug).
- To use `terminator.config` file the terminal emulator [__terminator__](https://terminator-gtk3.readthedocs.io/en/latest/) should be installed.

Also you can follow the instructions below:

### powerline-shell

Run the following commands:

```bash
pip install powerline-shell
sudo apt install fonts-powerline
```
*For powerline-shell works it is need to __logout__ and __login__ after install it.*

To use it with _WSL_ and _Windows Terminal_ you have to download the powerline font called _AnonymousPro_ from [here](https://github.com/ggrbill/fonts/tree/master/AnonymousPro) and install it manually in your **Windows 10**.

### vim-plug

Run the following command:

```bash 
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```
After that, type `:PlugInstall` inside *vim* editor in *normal mode*.

### terminator

To install it, run the command below:
```bash 
sudo apt install terminator
```

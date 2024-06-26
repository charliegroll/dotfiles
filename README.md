### Homebrew
1. Install [Homebrew](https://brew.sh/)
1. `mkdir -p ~/Developer/charliegroll`
1. `cd $_`
1. clone this repo 
1. `brew bundle install --file=dotfiles/Brewfile`
   ([docs](https://docs.brew.sh/Manpage#bundle-subcommand))
1. `cd ~`
1. `ln -s Developer/charliegroll/dotfiles/vimrc .vimrc`
2. `ln -s Developer/charliegroll/dotfiles/zshrc .zshrc`
1. `ln -s Developer/charliegroll/dotfiles/config/* ~/.config/`

#### To update ([more info](https://gist.github.com/ChristopherA/a579274536aab36ea9966f301ff14f3f))

- `brew bundle dump --file=./Brewfile --force`

### asdf

- `asdf plugin add nodejs https://github.com/asdf-vm/asdf-nodejs.git`

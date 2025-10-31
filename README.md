Neovim configuration

sudo add-apt-repository ppa:neovim-ppa/stable -y
sudo apt update
sudo apt install make gcc ripgrep unzip git xclip neovim

git clone --depth 1 https://github.com/wbthomason/packer.nvim\
 ~/.local/share/nvim/site/pack/packer/start/packer.nvim


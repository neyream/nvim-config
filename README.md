sudo pacman -S neovim
git clone https://github.com/neyream/nvim-config.git ~/.config/nvim
nvim --headless "+Lazy! sync" +qa

# dotfiles

1. `sudo apt install yadm`
2. `yadm clone https://github.com/johannesfknudsen/dotfiles.git`
3. `sudo apt install zsh`
4. `chsh -s $(which zsh)`
5. `sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
6. `git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions`
7. `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting`
8. `git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k`
9. `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/master/install.sh | bash`
10. `nvm install --lts` & `nvm alias default node` & `nvm use --lts`
11. `corepack enable pnpm`
12. `corepack prepare pnpm@latest --activate`

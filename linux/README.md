# Installed custom packages on system
docker  
dotnet  
fzf  
gh  
git  
npm  
nuget  
nvm  
sdkman  
ssh  
stow -> https://www.youtube.com/watch\?v\=y6XCebnB9gs  
tmux  
zsh -> https://blog.joaograssi.com/windows-subsystem-for-linux-with-oh-my-zsh-conemu/  

# Useful commands
```bash
wslpath // translates linux path to windows one (wsl)
sc.exe config wslservice start= demand // fix wsl (cmd)
```

# Install ZSH
```bash
sudo apt install zsh
chsh -s $(which zsh)
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
# Install, download and set in terminal those fonts: https://github.com/romkatv/powerlevel10k#fonts
source ~/.zshrc
```
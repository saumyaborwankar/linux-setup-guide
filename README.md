# linux-setup-guide
```
sudo apt update
```

# github desktop
```
sudo wget https://github.com/shiftkey/desktop/releases/download/release-3.1.1-linux1/GitHubDesktop-linux-3.1.1-linux1.deb 
sudo apt-get install gdebi-core -y
sudo gdebi GitHubDesktop-linux-3.1.1-linux1.deb -y
```

# slack
```
sudo gdebi GitHubDesktop-linux-3.1.1-linux1.deb -y
```

# vscode
```
sudo gdebi GitHubDesktop-linux-3.1.1-linux1.deb -y
```

# git 
```
sudo apt install git -y
```

# nodejs
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.6/install.sh | bash
nvm install --lts
```

# zsh + oh-my-zsh
```
sudo apt install zsh -y
chsh -s $(which zsh)
sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
Modify ~/.zshrc file to include plugin=(git aws) ZSH_THEME="(yet to select fav)"
Modify ~/.bashrc at end write ``` exec zsh ```


# aws setup
```
curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
sudo apt-get install unzip -y
unzip awscliv2.zip
sudo ./aws/install
```


# ubuntu_config

`sudo apt update && sudo apt upgrade && sudo apt install curl wget`


# Node.js

`curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash -`

`sudo apt-get install -y nodejs`


# Yarn

`curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -`

`echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list`

`sudo apt update && sudo apt install yarn`


# Typescript

`sudo npm i -g typescript`


# VSCode

```
sudo wget -O - https://tagplus5.github.io/vscode-ppa/ubuntu/gpg.key | sudo apt-key add - && \
sudo wget -O /etc/apt/sources.list.d/vscode.list https://tagplus5.github.io/vscode-ppa/ubuntu/vscode.list && \
sudo apt update &&
sudo apt install code
```

# Webstorm

https://www.jetbrains.com/help/webstorm/installation-guide.html#standalone


# Chrome

`cd Downloads`

`wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb`

`sudo dpkg -i --force-depends google-chrome-stable_current_amd64.deb`


# SSH keys

`ssh-keygen`

`cat ~/.ssh/id_rsa.pub`


# KeeWeb

```
sudo wget -O - https://tagplus5.github.io/keeweb-ppa/ubuntu/gpg.key | sudo apt-key add - && \
sudo wget -O /etc/apt/sources.list.d/keeweb.list https://tagplus5.github.io/keeweb-ppa/ubuntu/keeweb.list && \
sudo apt update && \
sudo apt install keeweb-desktop
```





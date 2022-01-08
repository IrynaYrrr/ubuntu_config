# ubuntu_config

```
sudo apt update && sudo apt upgrade && sudo apt install curl wget git gnupg
```


# SSH keys

## create

```
ssh-keygen
```

## show public key

```
cat ~/.ssh/id_rsa.pub
```


# Node.js

```
curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash -
```

```
sudo apt-get install -y nodejs`
```


# Yarn

```
curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
```

```
echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
```

```
sudo apt update && sudo apt install yarn
```


# Typescript

```
sudo npm i -g typescript
```


# VSCode

```
sudo wget -O - https://tagplus5.github.io/vscode-ppa/ubuntu/gpg.key | sudo apt-key add - && \
sudo wget -O /etc/apt/sources.list.d/vscode.list https://tagplus5.github.io/vscode-ppa/ubuntu/vscode.list && \
sudo apt update &&
sudo apt install code
```


# Webstorm

```
sudo snap install webstorm --classic
```


# Chrome

```
cd Downloads
```

```
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
```

```
sudo dpkg -i --force-depends google-chrome-stable_current_amd64.deb
```


# KeeWeb

```
sudo wget -O - https://tagplus5.github.io/keeweb-ppa/ubuntu/gpg.key | sudo apt-key add - && \
sudo wget -O /etc/apt/sources.list.d/keeweb.list https://tagplus5.github.io/keeweb-ppa/ubuntu/keeweb.list && \
sudo apt update && \
sudo apt install keeweb-desktop
```


# Robo3T

```
sudo snap install robo3t-snap
```


# Postman

```
sudo snap install postman
```


# MongoDB

## install

```
wget -qO - https://www.mongodb.org/static/pgp/server-5.0.asc | sudo apt-key add -
```

```
echo "deb [ arch=amd64,arm64 ] https://repo.mongodb.org/apt/ubuntu focal/mongodb-org/5.0 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-5.0.list
```

```
sudo apt-get update
```

```
sudo apt-get install -y mongodb-org
```

```
sudo systemctl start mongod
```

```
sudo systemctl enable mongod
```

## check status

```
sudo systemctl status mongod
```

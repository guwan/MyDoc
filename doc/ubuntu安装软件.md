## 安装java
sudo apt install openjdk-20-jre-headless

## 安装nginx

sudo apt install nginx-extras


## 安装node
--参考网址：https://github.com/nodesource/distributions
curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash - &&\
sudo apt-get install -y nodejs

## 安装yarn
corepack prepare yarn@stable --activate

## 安装zsh
sudo apt install zsh

## 安装Oh My Zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

## zsh和bash互切
### 切换bash
` exec bash `
### 切换zsh
` exec zsh `

## 安装mariadb
sudo apt install mariadb-server

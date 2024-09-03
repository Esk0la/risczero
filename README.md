# Risczero
![image](https://github.com/user-attachments/assets/ba63ef9d-0307-455e-b3b2-2826fc8d44cd)

Hardware Requirements

Memory: 8GB++ RAM or 4GB RAM
Bandwidth: 25 Mbps Download/Upload

Website: https://www.risczero.com/

Detail: https://www.risczero.com/blog/ceremony-contribution-public-instructions

Guide: https://p0tion.super.site/ce8f7047468b41239dc512919644535c

‼️ GitHub Account Requirements: You must have at least 1 publicly accessible repository. You must be following at least 5 GitHub users. You must have at least 1 follower.

Installation

```
curl -sL https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.0/install.sh | sh -
source ~/.profile
mkdir p0tion-tmp
cd p0tion-tmp
nvm install 16.20
nvm use 16.20
npm install @p0tion/phase2cli
```
Verify GitHub Account

When you enter the code, it will give you a code on the page. you go to this link and paste that code. https://github.com/login/device

```
npx phase2cli auth
```
Contribution
```
screen -S risczero
```
```
npx phase2cli contribute
```
Follow the instructions and continue until you see the message "You must wait for xxx participants (~xx:xx:xx:xx:00 (dd/dd/dd/ss))"

Press and hold ctrl and press a d to exit the screen

To check your progress
```
screen -r risczero 
```
Run the following code after successful completion
```
npx phase2cli clean
```

# Node安装
本文仅介绍windows WSL安装方式
## NVM介绍
nvm是node的版本管理工具，使用nvm可以方便切换各个版本的node。
地址： https://github.com/nvm-sh/nvm
### NVM 安装

```sh
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash

wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash
```
以上两个命令二选一

注意，有时脚本会443,可以手动下载后运行。

### 安装node

 nvm install node # "node" is an alias for the latest version
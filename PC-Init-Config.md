# PC Initial and Configuration

## Homebrew

> <https://brew.sh/>

Homebrew是mac中一款软件安装工具，类似Linux中的apt-get、yum等。

### 安装

官方给出的安装命令为：

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

如果没有VPN，通过官网的命令安装会因为网络隔断而失败。我们可以从国内镜像源安装：

```sh
/bin/zsh -c "$(curl -fsSL https://gitee.com/cunkai/HomebrewCN/raw/master/Homebrew.sh)"
```

### 使用

```sh
# 安装
brew install node
```

## Node/Npm

与Node.js相关的一些组件。

### 安装

mac可通过brew来安装：`brew install node`，`node`安装好之后会自带`npm`。
安装完成后可通过`node -v`和`npm -v`查看版本。

## Hexo

> <https://hexo.io/zh-cn/>

Hexo是一款好用的博客框架，它能够快速的将你写的Markdown文件渲染成Html静态页面。

```sh
# 安装hexo cli
npm install hexo-cli -g
# 初始化一个项目，项目名为blog
hexo init blog
cd blog
npm install
# 本地启动一个服务，可在浏览器预览博客网站效果
hexo server
# 创建一个markdown文件
hexo new "File Name"
# 为markdown文件生成html页面
hexo g
```

### 部署到Github

### 归档管理

# Git学习教程（新手入门易上手版）

## 写在前面

### 1. Git是什么？

Git是一个版本控制工具。简单的说，就是相当于一个网盘功能，但主要只能存储文档类型或app安装文件。

### 2. Git工作原理

在远程服务器（仓库管理器）网站上（如GitHub、Gitee、GitLab等）新建一个repository，然后可以在任意电脑上登录网站，将其想要修改的内容下载下来，修改完成后再上传回去。

### 3. 选择Git的理由

主要用于记录平时的工作内容，且偶尔会学习LaTex，这样就可以随时查看了

## 一、准备工作

### 1. 安装Git

可从https://git-scm.com/downloads下载，然后一路默认安装

使用`win+R`快捷键，输入`cmd`回车，在命令行窗口输入`git -v`，出现版本信息即安装成功

（这一步没试过是不是必须，反正后续也使用不到命令行，命令对于新手不太友好）

### 2. 注册GitHub账号

温馨提示：此步骤或许需要VPN翻墙

输入网址：https://github.com/按提示输入邮箱和密码，用户名注册即可。

### 3. 安装GitHub客户端

可以从https://github.com/apps/desktop下载安装

## 二、具体操作步骤

#### 1. 在GitHub网站上新建一个repository

![image-20250102110749772](C:\Users\liushuolin\AppData\Roaming\Typora\typora-user-images\image-20250102110749772.png)

如上图，在dashboard页面下方，点击new，然后看下图

![image-20250102111122045](C:\Users\liushuolin\AppData\Roaming\Typora\typora-user-images\image-20250102111122045.png)

#### 2. 从GitHub拉取文件到本地

##### 方式一：

点击最右侧头像

![image-20250102111401341](C:\Users\liushuolin\AppData\Roaming\Typora\typora-user-images\image-20250102111401341.png)

选择your repositories

![image-20250102111438216](C:\Users\liushuolin\AppData\Roaming\Typora\typora-user-images\image-20250102111438216.png)

就能看到自己所有创建的repository，任意点击其中一个，如图点取

![image-20250102111612482](C:\Users\liushuolin\AppData\Roaming\Typora\typora-user-images\image-20250102111612482.png)

##### 方式二（推荐）

打开GitHub desktop，依次点击File->clone a repository

![image-20250102111907747](C:\Users\liushuolin\AppData\Roaming\Typora\typora-user-images\image-20250102111907747.png)

如上图，可选择GitHub.com标签，点选自己所需要的repository

也可以在URL标签下，第一个框中将GitHub上项目地址复制上，在第二个框中选择本地存储的文件夹，再点击clone即可完成


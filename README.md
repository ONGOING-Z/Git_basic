[TOC]

# Git_basic

Git的一些基本使用

### 1. git 查看修改用户名与密码
- 查看用户名
```
git config --global user.name
```
- 修改用户名
```
git config --global user.name "your name"
```
- 查看邮箱地址
```
git config --global user.email
```
- 修改邮箱地址
```
git config --global user.email "your email address"
```

### 2. git 本地与远程仓库关联与解除
- 查看远程仓库信息
```
git remote -v
```
- 建立新仓库
```
在github中建立一个新的仓库
可以不要README.md文件
```
- 关联
```
git remote add origin git@github.com:your_name/repository_name.git
```
- 解除关联
```
git remote remove origin
```

### 3. GitHub快速更换绑定邮箱
(1)点击头像
(2)setting
(3)Email
(4)Add email address
(5)新邮箱验证，返回github，将新邮箱验证Set Primary.

### 4. git 推送
```
git push -u origin master
```

### 5. github 如何删除仓库
（1）settings
（2）页面最下方'Delete this repository'

### 6. 查看本地与远程的连接
```
ssh -T git@github.com
```

### 7. 在本地配置公钥
```
ssh-keygen -t rsa -C email_address
```

### 8. 重命名

- git mv: move or rename a file, a directory.

- description

```
git mv <source> <destination>
git mv <source> <destination directory>
```

*暂时还没看懂重命名文件夹是怎么做的。*

### 9. github刷新

在自己电脑本地`push`完文件后，想要在github中看看效果，

*不要直接按F5进行整个网页的刷新*，

点击自己**仓库的名称链接**进行刷新，这样会比较快。

### 10. git基本操作

```
# 初始化仓库
git init
# 取消初始化仓库
rm -rf .git/
# 查看仓库状态（哪些文件提交了，哪些文件未提交）
git status
# 添加文件至提交列表
git add filename
```


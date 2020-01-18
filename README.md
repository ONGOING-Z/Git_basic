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


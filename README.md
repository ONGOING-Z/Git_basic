# Using_Git
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
- 关联
```
git remote add origin git@github.com:your_name/repository_name.git
```
- 解除关联
```
git remote remove origin
```


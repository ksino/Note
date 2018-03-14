[TOC]

## 添加公钥
* <http://blog.csdn.net/fenghuibian/article/details/73350890>
* 本地生成ssk-key
* 添加公钥到github

## 初始化git仓库
`git init`

## 添加文件
`git add <file>`

## 提交
`git commit`

## 同步到远程库
* 需要新建好Repository
`git remote add origin git@github.com:ksino/maxone.git`

* 推送到远程库

> 第一次使用随便设置email, username

```
git config --global user.name "kim"
git config --global user.email "kim@debian.com"
```
`git push -u origin master`

* 克隆一个库
`git clone git@github.com:ksino/maxone.git`

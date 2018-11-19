# git 

## 使用git 从本地上传到github中

 ```DIZ
(先在github中创建一个没有初始化过的储存库  然后复制对应的ssh密令)
1.先在本地创建一个文件夹
2.打开文件夹 打开git命令工具
3.git init
4.git add .
5.git commit -m "...."
6.在github上创建一个空仓库 用于存放项目代码
7.git remote add origin(别名) + (SSH地址 远程仓库地址)   (设置仓库别名)
8.git remote(就有一个origin初始地址)
9.git push origin master   (将代码推送到github中)
此时已经上传成功
(push origin master 是传送文件)

 ```

## 从github上拉文件到本地

```
1.找到对应的文件
2.复制并克隆
3.找到一个文件夹  在此打开git  
4.git clone + 远程仓库地址
5.cd +克隆下来的文件夹 (进入克隆的文件夹中)
6.git add .
7.git commit -m "..."
8.git push origin master 
```


# vscode 连接 GitHub
## 一、Git配置
1 .下载git，并在bash中输入以下命令配置用户名和邮箱
```
git config --global user.name "qiumuch"
git config --global user.email "zhyuzh3d@hotmail.com"
```
2 .输入 `git init` 初始化仓库，生成.git文件夹
```
git init
```
3 .ssh方式连接github，参考 [这里1](https://blog.csdn.net/piglite/article/details/88222695) [这里2](https://www.jianshu.com/p/f836da434e18)，以及 [新手常犯问题](https://blog.csdn.net/yushuangping/article/details/84240863)
```
git remote add origin git@github.com:qiumuch/2020_me.git
```
4 .https方式连接github，参考 [这里](https://www.jianshu.com/p/bf37a3fdf480)
```
git remote add origin https://github.com/qiumuch/2020_me.git
```

## 二、vscode中提交代码

1 .`commit all` 并填写提交信息

2 .先 `pull` 拉取，然后再 `push` 推送

3 .[branch报错](https://www.cnblogs.com/x-llin/p/11851662.html)

# 2020/3/chu22周末学习内容

## 安装软件

cmder，typora，git

## 学习git内容

### 注意事项

.git这个目录是Git来跟踪管理版本库的，没事千万不要手动修改这个目录里面的文件，不然改乱了，就把Git仓库给破坏了。

### 告诉它你的信息

```
$ git config --global user.name "your name"
$ git config --global user.email "your email"
```

### 创建版本库

```
$ mkdir learngit  
$ cd learngit     
$ pwd       用于显示当前目录
$ git init  初始化让其变成一个git可以管理的仓库
```

### 新建一个文件，把文件添加到版本库

要在learngit目录下（子目录也行）进行创建

```
$ git add readme.md
```

需要在仓库文件夹进行操作

```
$ git commit -m"本次提交的说明"
[master (root-commit) eaadf4e] wrote a readme file
 1 file changed, 2 insertions(+)1个文件被改动 插入了两行内容
 create mode 100644 readme.txt
```


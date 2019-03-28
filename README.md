#### 一.常用命令
1. 创建空文件夹
> $ mkdir 文件夹名称   例：mkdir sun 
2. 显示当前路径
> $ pwd         
3. 显示当前目录
> $ ls                
4. 显示隐藏文件
> $ ls -a      
5. 提示下一步操作     
> $ git status   
6. 回到根路径
> $ cd ~

#### 二.github上新建一个空仓库，上传本地文件 进行 修改  ，提交， 更新等
1. 创建README.md文件（在本地已有或者新创建文件夹中创建README.md）
> $ echo "# 1" >> README.md
2. 初始化git
> $ git init
3. 提交文件
> $ git add "README.md"或者 git add .
4. 为你提交的文件 进行描述
> $ git commit -m "提交README.md"
5. 为本地提供github仓库地址
> $ git remote add origin git@github.com:xixixixixixixixixi/git-cmd.git
6. 进行提交
> $ push -u origin master
7. 本地从仓库进行拉取更新
> 首先cd到该文件夹 执行 $ git pull
8 .本地有所更改提交到仓库
> 首先cd到该文件夹下  $ git add . $ git  commit -m "11"  $ git push

#### 三.克隆github仓库
创建空文件夹  
> $ mkdir  sun
> $ git clone  git@github.com:xixixixixixixixixi/git-cmd-.git

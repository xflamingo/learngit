GIT commond summary
GIT 命令总结

1.设置
    $ git config --global user.name "Your Name"
    $ git config --global user.email "email@example.com"
2.初始化仓库
    $ git init
3.添加文件
    $ git add readme.txt
4.提交修改并添加提交说明
    $ git commit -m '说明'
5.查看当前状态
    $ git status
6.查看文件变化
    $ git diff readme.txt
7.查看日志
    $ git log
8.版本回退
    $ git reset --hard HEAD^        //HEAD为当前版本，HEAD^为上个版本，HEAD^^为上上个版本，同理以此类推
9.回退到到特定版本
    $ git reset --hard 1094a        //最后参数为版本号的一部分
10.查看命令记录
    $ git reflog
11.丢弃工作区的修改
    $git checkout --readme.txt
12.撤销暂存区的修改
    $git reset HEAD <file>
13.删除文件
    $git rm readme.txt
14.
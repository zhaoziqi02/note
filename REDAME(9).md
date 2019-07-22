
#上传文件：
    git init  //初始化本地仓库

    git add .   //从编辑区添加到暂存区

    git commit -m '命名'  //暂存区提交到分支

    git push -u    //同步远程仓库

    git clone “网址”  //克隆项目

    git pull   //拉取项目代码
##分支
    git branch    //查看分支

    git branch "命名"  //创建分支

    git checkout "命名"  //切换分支
#删除方法
    $ git add * //把本地仓库的文件上传到缓存。

    $ git commit -m 'del' //把第一步上传到
    缓存的东西上传到本地仓库，其中'del'是操作标识，
    内容随便填，方便用户观看。

    $ git push origin master //把本地仓库的文件
    上传到远程仓库。
#表格
    姓名|技能|排行
    --|:--:|--:
    刘备|哭|大哥
    关羽|打|二哥
    张飞|骂|三弟
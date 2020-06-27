# git

> git的相关操作

图形界面工具推荐 sourcetree



> 初始化一个git
``` bash
git init
```


> 添加远程地址
``` bash
git remote add origin https://github.com/adminparry/git.git
```

> 克隆

``` bash
git clone https://github.com/adminparry/git.git
```

> 克隆指定文件夹

``` bash

git init
# 初始化
git remote add origin  https://github.com/adminparry/git.git
# 指定源

git config core.sparsecheckout true
echo "docs*" >> .git/info/sparse-checkout

git pull origin master

```

> 查看变化
``` bash
git status

```

> 提交
``` bash

git add .
# 添加文件
git commit -am "add a beautiful place"

```


# git使用技巧

```
// 本地创建README.md文件
echo "# git-" >> README.md
//项目本地初始化 git
git init
//git添加README.md
git add README.md
//初始化提交
git commit -m "first commit"
//git添加远程仓库
git remote add origin https://github.com/haixiangyuan/git-.git
//本地push远程分支
git push -u origin master
```

```
//远程仓库路径查询
git remote -v
//添加远程仓库
git remote add origin <你的项目地址>
//删除指定的远程
git remote rm origin
```


# subtreeTestParent
subtreeTestParent,测试subtree的功能，

# 将subtreeTestChild仓库项目的 文件 复制到 subtreeTestParent的sub文件夹下面  
## (--squash参数表示不拉取历史信息，而只生成一条commit信息。)   


```
git subtree add --prefix=sub/child https://github.com/Heyff12/subtreeTestChild.git master --squash
```


## 从subtreeTestChild源仓库拉取更新
```
git subtree pull --prefix=sub/child https://github.com/Heyff12/subtreeTestChild.git master --squash
```


## 推送修改到源仓库subtreeTestChild
```
git subtree push --prefix=sub/child https://github.com/Heyff12/subtreeTestChild.git master
```
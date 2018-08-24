# subtreeTestChild
subtreeTestChild,测试subtree功能  

# 在吃了点更改child文件，并push,查看 parent的内容是否变化  
##  在parent执行
```
git subtree pull --prefix=sub/child https://github.com/Heyff12/subtreeTestChild.git master --squash
```

# 在parent更改child文件，并push,查看 child的内容是否变化  
##  在parent执行
```
git subtree push --prefix=sub/child https://github.com/Heyff12/subtreeTestChild.git master
```

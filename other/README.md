# 一. 梦开始的地方

## 1. 卿子小屋

​	![卿子小屋](./imgs/卿子小屋.png)

> + git命令

```bash
git add *
git commit -m "first-commit:qingzi's home" *
git remote  add zhlangArchive  git@github.com:cat2021-px/zhilang_archive.git
git push zhlangArchive master
```

## 2. 大将

![](./imgs/河原.png)

```bash
$ git reflog
# a19f15e 大将的版本id
a19f15e (HEAD -> master, zhilangArchive/master) HEAD@{0}: commit: second-commit:dajiang
63148a5 HEAD@{1}: commit (initial): first-commit:qingzi's home

```



## 3. 长枪

![](./imgs/长枪.png)

```bash
$ git reflog
7927db9 (HEAD -> master, zhilangArchive/master) HEAD@{0}: reset: moving to 7927db9
a19f15e HEAD@{1}: reset: moving to a19f15e
# 长枪id 7927db9
7927db9 (HEAD -> master, zhilangArchive/master) HEAD@{2}: commit: third-commit:changqiang
a19f15e HEAD@{3}: commit: second-commit:dajiang
63148a5 HEAD@{4}: commit (initial): first-commit:qingzi's home

```



## 4. 八重塔忍者

![](./imgs/八重塔.png)
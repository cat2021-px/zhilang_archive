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

```bash
$ git reflog
# 八重他忍者id b3374b2
b3374b2 (HEAD -> master, zhilangArchive/master) HEAD@{0}: commit: fourth-commit:bachongtarenzhe
7927db9 HEAD@{1}: reset: moving to 7927db9
a19f15e HEAD@{2}: reset: moving to a19f15e
7927db9 HEAD@{3}: commit: third-commit:changqiang
a19f15e HEAD@{4}: commit: second-commit:dajiang
63148a5 HEAD@{5}: commit (initial): first-commit:qingzi's home
```

## 5. 燃烧房子过桥相扑选手

![](./imgs/火房子相扑选手.png)

```bash
# fifth-commit:huoFangZiXiangPu 225db52
225db52 (HEAD -> master, zhilangArchive/master) HEAD@{0}: commit: fifth-commit:huoFangZiXiangPu
b3374b2 HEAD@{1}: commit: fourth-commit:bachongtarenzhe
7927db9 HEAD@{2}: reset: moving to 7927db9
a19f15e HEAD@{3}: reset: moving to a19f15e
7927db9 HEAD@{4}: commit: third-commit:changqiang
a19f15e HEAD@{5}: commit: second-commit:dajiang
63148a5 HEAD@{6}: commit (initial): first-commit:qingzi's home

```

## 6. 虎口阶梯-赤鬼

![](./imgs/虎口阶梯赤鬼.png)

```bash
# 赤鬼id 2e475e9
2e475e9 (HEAD -> master, zhilangArchive/master) HEAD@{0}: commit: sixth-commit:chigui
225db52 HEAD@{1}: commit: fifth-commit:huoFangZiXiangPu
b3374b2 HEAD@{2}: commit: fourth-commit:bachongtarenzhe
7927db9 HEAD@{3}: reset: moving to 7927db9
a19f15e HEAD@{4}: reset: moving to a19f15e
7927db9 HEAD@{5}: commit: third-commit:changqiang
a19f15e HEAD@{6}: commit: second-commit:dajiang
63148a5 HEAD@{7}: commit (initial): first-commit:qingzi's home
```

## 7. 赤鬼之后

![](./imgs/赤鬼之后的大将.png)

```bash
$ git reflog
# 武士大将 5c3438c
5c3438c (HEAD -> master, zhilangArchive/master) HEAD@{0}: commit: seventh:commit:chiguizhihou
2e475e9 HEAD@{1}: commit: sixth-commit:chigui
225db52 HEAD@{2}: commit: fifth-commit:huoFangZiXiangPu
b3374b2 HEAD@{3}: commit: fourth-commit:bachongtarenzhe
7927db9 HEAD@{4}: reset: moving to 7927db9
a19f15e HEAD@{5}: reset: moving to a19f15e
7927db9 HEAD@{6}: commit: third-commit:changqiang
a19f15e HEAD@{7}: commit: second-commit:dajiang
63148a5 HEAD@{8}: commit (initial): first-commit:qingzi's home
```

## 8. 初遇无首

![](./imgs/初遇无首.png)

```bash
$ git reflog
# 无首id feea4ad
feea4ad (HEAD -> master, zhilangArchive/master) HEAD@{0}: commit: eighth-commit:chuyuwushou
5c3438c HEAD@{1}: commit: seventh:commit:chiguizhihou
2e475e9 HEAD@{2}: commit: sixth-commit:chigui
225db52 HEAD@{3}: commit: fifth-commit:huoFangZiXiangPu
b3374b2 HEAD@{4}: commit: fourth-commit:bachongtarenzhe
7927db9 HEAD@{5}: reset: moving to 7927db9
a19f15e HEAD@{6}: reset: moving to a19f15e
7927db9 HEAD@{7}: commit: third-commit:changqiang
a19f15e HEAD@{8}: commit: second-commit:dajiang
63148a5 HEAD@{9}: commit (initial): first-commit:qingzi's home
```

## 9. 蚺蛇重藏

![](./imgs/蟒蛇重藏.png)

```bash
$ git reflog
# 蚺蛇id d742d2b
d742d2b (HEAD -> master, zhilangArchive/master) HEAD@{0}: commit: tenth-commit:ranshezhongzang
feea4ad HEAD@{1}: commit: eighth-commit:chuyuwushou
5c3438c HEAD@{2}: commit: seventh:commit:chiguizhihou
2e475e9 HEAD@{3}: commit: sixth-commit:chigui
225db52 HEAD@{4}: commit: fifth-commit:huoFangZiXiangPu
b3374b2 HEAD@{5}: commit: fourth-commit:bachongtarenzhe
7927db9 HEAD@{6}: reset: moving to 7927db9
a19f15e HEAD@{7}: reset: moving to a19f15e
7927db9 HEAD@{8}: commit: third-commit:changqiang
a19f15e HEAD@{9}: commit: second-commit:dajiang
63148a5 HEAD@{10}: commit (initial): first-commit:qingzi's home

```

## 10. 蝶夫人

![](./imgs/蝶夫人.png)

```bash
# 蝶夫人id bd90d20
bd90d20 (HEAD -> master, zhilangArchive/master) HEAD@{0}: commit: eleventh-commit:dieFuRen
d742d2b HEAD@{1}: commit: tenth-commit:ranshezhongzang
feea4ad HEAD@{2}: commit: eighth-commit:chuyuwushou
5c3438c HEAD@{3}: commit: seventh:commit:chiguizhihou
2e475e9 HEAD@{4}: commit: sixth-commit:chigui
225db52 HEAD@{5}: commit: fifth-commit:huoFangZiXiangPu
b3374b2 HEAD@{6}: commit: fourth-commit:bachongtarenzhe
7927db9 HEAD@{7}: reset: moving to 7927db9
a19f15e HEAD@{8}: reset: moving to a19f15e
7927db9 HEAD@{9}: commit: third-commit:changqiang
a19f15e HEAD@{10}: commit: second-commit:dajiang
63148a5 HEAD@{11}: commit (initial): first-commit:qingzi's home
```



## 11. 金刚寺无首

![](./imgs/金刚寺无首.png)




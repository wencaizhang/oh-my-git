
# 查看提交记录

### 1. 查看某个文件的提交记录

修改还未提交到暂存区的时候：

```bash
git diff <filename>
```


提交到暂存区之后：

```bash
git diff --cache <filename>
```

或者

```bash
git diff --staged <filename>
```

commit 之后：

```bash
git log -p <filename>
```
### 2. 查看某人的提交记录

```bash
git log --stat --author=someone
```

### 3. 查看某次 commit 的提交记录

```bash
git show <commit-hash-id>
```

或者

```bash
git log -p <commit-hash-id>
```


## 参考

[更好的git Log](http://strivingboy.github.io/blog/2014/09/29/better-git-log/)
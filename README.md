
# gitruth

----

Clean git files forever. Like
[Ministry of Truth](http://en.wikipedia.org/wiki/Ministry_of_Truth)

## Install

```bash
$ npm install gitruth -g
```

## Usage

```bash
$ gitruth path/to/file
$ gitruth -h
```

## Note

由于 GitHub 的缓存机制，如果你拥有历史版本信息，仍可以通过这个历史版本信息查看
历史提交的版本，即使这个版本在仓库中被修改或删除。

例如

```
https://github.com/hotoo/exists-repo/blob/760efd0adde3893c88a91fe45370e7b690cb5ca6/not-exists-file
```

即使 `760efd0adde3893c88a91fe45370e7b690cb5ca6` 这个版本已经不存在，但仍可以
直接访问。

可以通过删除并重新创建仓库的方式清理掉这个历史版本，
但要**注意**，这样会删除这个仓库的 Issues, Wikis 和 Releases 等。

## Thanks

* [Remove sensitive data](https://help.github.com/articles/remove-sensitive-data)
* [Git如何永久删除文件(包括历史记录)](http://www.cnblogs.com/shines77/p/3460274.html)

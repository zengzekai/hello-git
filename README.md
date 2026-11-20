# hello-git

我的第一个 Git 仓库，用来熟悉 Git 的基本操作。

## 项目说明
这是一个最小练习项目，包含三个文件：

- `hello.py` —— 打印一行中文，验证 Python 环境
- `.gitignore` —— 让 Git 忽略不该提交的缓存和密钥文件
- `README.md` —— 你正在读的这个说明文件

## 常用命令速查

```bash
git status              # 看当前改了什么
git add .               # 把改动加入暂存区
git commit -m "说明"    # 提交一次快照
git log --oneline       # 看提交历史
git push                # 推送到 GitHub
```

## 为什么要有 .gitignore

不该进仓库的东西（虚拟环境、缓存、API 密钥）一旦提交上去，就永远留在历史记录里，
即使后面删掉也能被翻出来。所以从第一个仓库开始就要养成习惯。

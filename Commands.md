## Lamarck &nbsp; &nbsp; &nbsp; 2025-11-02
#### 该文档用于记录Git的常用命令
---

*01  查看Git版本*
```bash
git -v
```

*02  配置用户名称&邮箱*
```bash
# 配置名称
git config --global user.name LamarckLab

# 配置邮箱
git config --global user.email 704021302@qq.com

# 配置http和https访问时的走的代理端口 (clash默认是7890, clash verge默认是7897)
git config --global http.proxy http://127.0.0.1:7897
git config --global https.proxy http://127.0.0.1:7897

# 查看全局配置信息
git config --global --list
```

*03  Git仓库基础操作*
```bash
# 初始化一个仓库 (在某个文件夹中)
git init

# 克隆一个远程仓库
git clone https://github.com/LamarckLab/033_Git_notes.git

# 查看当前仓库的状态
git status

# 把更新后的文件添加到暂存区
git add .

# 把暂存区的内容传到本地Git仓库
git commit  # 随后会自动进入vim编辑commit的注释
git commit -m "lamarck's commit"  # 直接提交

# 查看提交日志
git log
```

*04  把本地仓库内容推送到远程仓库*
```bash
git push
```














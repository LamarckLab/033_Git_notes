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

*03  新建Git仓库*
```bash
git init
```













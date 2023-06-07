1. git 是一个免费开源的分布式版本控制系统
2. *github*,*gitlab*,*gitee*都是代码托管平台
   
## 配置命令
```bash
git config --global [key] [value] #设置键和属性
git config --global --unset key # 删除某个键和对应属性
git config --[global, system, local] --list # 查看config信心
git init # 创建git仓库
git clone <url.git> # 克隆某个项目
git add <name> # 跟踪文件
```

#### 只有被跟踪的状态才会在版本中
```
未跟踪 -> 缓存(git add) -> 
未跟踪(git reset HEAD) <- 缓存

1.未跟踪
2.未修改
3.已修改
4.缓存
```
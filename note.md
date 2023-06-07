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
git commit <filename> # 提交
git reset head~ --soft # 取消提交 无法撤销第一次提交
git status # 查看文件状态
git diff # 查看区别
git log # 提交日志
git remote add <local_name> <url.git> # 添加远程仓库
git remote rename <name> <new_name>
git push <respoityry_name> <master>
git branch --list # 查看分支
git branch <branch_name> # 创建新的分支
git branch checkout <branch_name> # 切换当前分支git
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
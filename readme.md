# 一. 配置全局
## 设置用户名/邮箱
* git config --global user.name "zhangsan"
* git config --global user.email "zhansan@163.com"
## 修改用户名/邮箱
* git config --global --replace-all user.name "lisi"
* git config --global --replace-all user.email "lisi@162.com"
## 查看全局设置
* git config --global -l/(list)
# 二. 提交
## 1. git add \<filename>
## 2. git commit \<filename>
## 3. git push
# 三. 撤销
1. 撤销工作区修改内容
* git checkout -- \<filename>
2. 撤销暂存区修改内容
* git reset HEAD \<filename>

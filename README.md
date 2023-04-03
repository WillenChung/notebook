# git使用(Ubuntu)

#### 安装
sudo apt install git 
#### 初次使用
git config --global user.name "用户名"  
git config --global user.email "邮箱"  
#### 创建目录
mkdir test  
cd test  
#### git初始化
git init  
#### 提交代码
git add .  
git commit -m "注释信息"  
#### 回滚代码
查看提交历史  
git reflog  
回滚  
git reset --hard 版本id  
#### 注意事项
回滚到之前版本未提交则会丢失  




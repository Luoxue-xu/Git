##命令解析
###初始化配置
```javascript
# 配置使用git仓库的人员姓名
git config --global user.name "Your Name Comes Here"
# 配置使用git仓库的人员email
git config --global user.email you@yourdomain.example.com
# 配置到缓存 默认15分钟
git config --global credential.helper cache
# 修改缓存时间
git config --global credential.helper 'cache --timeout=3600'
git config --global color.ui true
git config --global alias.co checkout
git config --global alias.ci commit
git config --global alias.st status
git config --global alias.br branch
# 设置Editor使用textmate
git config --global core.editor "mate -w"</p>
# 列举所有配置
git config -1
# 用户的git配置文件
~/.gitconfig

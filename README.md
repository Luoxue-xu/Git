<h1>命令解析</h1>
<h2>初始化配置</h2>
<p><i># 配置使用git仓库的人员姓名</i></p>
<p>git config --global user.name "Your Name Comes Here"</p>
<p><i># 配置使用git仓库的人员email</i></p>
<p>git config --global user.email you@yourdomain.example.com</p>
<p><i># 配置到缓存 默认15分钟</i></p>
<p>git config --global credential.helper cache</p>
<p><i># 修改缓存时间</i></p>
<p>git config --global credential.helper 'cache --timeout=3600'</p>
<p>git config --global color.ui true</p>
<p>git config --global alias.co checkout</p>
<p>git config --global alias.ci commit</p>
<p>git config --global alias.st status</p>
<p>git config --global alias.br branch</p>
<p><i># 设置Editor使用textmate</i></p>
<p>git config --global core.editor "mate -w"</p>
<p><i># 列举所有配置</i></p>
<p>git config -1</p>
<p><i># 用户的git配置文件</i></p>
<p>~/.gitconfig</p>
